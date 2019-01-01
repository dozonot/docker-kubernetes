FROM rails

RUN git clone https://github.com/dozonot/sample_app.git && \
    cd sample_app && \
    bundle update && \
    rails db:migrate

WORKDIR sample_app
CMD ["rails", "server"]

FROM pegi3s/fastqc:0.11.9

LABEL org.opencontainers.image.source https://github.com/junjun-zhang/bosc-cofest-wfpm

ENV PATH="/tools:${PATH}"

COPY *.py /tools/

ENTRYPOINT ["/usr/bin/env"]

CMD ["/bin/bash"]

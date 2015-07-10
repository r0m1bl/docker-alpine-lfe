# Erlang
FROM r0m1bl/alpine-erlang

RUN git clone https://github.com/rvirding/lfe.git && cd lfe && make
RUN curl -L -o ./lfetool https://raw.github.com/lfe/lfetool/stable/lfetool && bash lfetool install && lfetool -x

ENTRYPOINT ["/bin/sh"]
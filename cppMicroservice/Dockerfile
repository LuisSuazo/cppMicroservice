FROM lsuazo/cppubuntu
 
COPY . /usr/src/cppmcs
WORKDIR /usr/src/cppmcs/libs
RUN sh build_dependencies.sh
WORKDIR /usr/src/cppmcs
RUN mkdir build
WORKDIR /usr/src/cppmcs/build
RUN cmake -G "Unix Makefiles" -DCMAKE_BUILD_TYPE=Debug ..
RUN make -j 8

CMD ["./micro-service"]

LABEL Name=micro-service-cpp Version=1

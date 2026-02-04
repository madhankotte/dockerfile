ARG VERSION
FROM amazonlinux:${VERSION:-9}
ARG  course="docker" \
     author="madhankotte"
ENV course=${course} \
    author=${author}

RUN  echo "Course Name is ${course} and Author is ${author}"
CMD [ "sleep", "1000" ]


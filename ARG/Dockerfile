ARG version=9
FROM almalinux:${version:-9}
ARG name="yash" \
    age="24"
ENV name=$name
RUN echo "name=$name , age=$age , version=$version"
CMD ["sleep" ,"200"]

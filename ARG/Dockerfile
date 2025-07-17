ARG version 
FROM almalinux:${version:-9}
ENV course="Devops" \
    duration="120 hrs"
ARG trainer="siva"
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"

CMD ["sleep", "1000"]
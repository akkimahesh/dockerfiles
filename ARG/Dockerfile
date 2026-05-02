ARG version
FROM almalinux:${version:-8}
ARG Name="Mahesh" \
    experience="2 year" \
    Designation="DevOps Engineer"
RUN echo "Name is: ${Name}, experience is: ${experience}, Designation is: ${Designation}"
CMD ["sleep", "200"]

#ARG is only available during build time and it is not persisted in the final image, while ENV is available during both build time and runtime and it is persisted in the final image.
ARG version
FROM almalinux:${version:9}  # ARG is forst instaruction only to provide version
ARG company=infosys
ENV COMPANYNAME=${company}
RUN echo "company name is ${company}"
CMD ["sleep" , "500"]
ARG version=9
FROM almalinux:${version}  
# ARG is the only instaruction that is declared infront of from and used in from
ARG company=infosys

# we cant access argument inside container,so passing it in ENV variables
ENV COMPANYNAME=${company}
RUN echo "company name is ${company}"
CMD ["sleep" , "500"]
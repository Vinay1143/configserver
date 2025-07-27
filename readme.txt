git hub configs url 
https://github.com/Vinay1143/myconfigserver.git


http://localhost:8089/loans/dev
check configs in this url

to fetch the configs from localfiles
search-locations: "file:///user//vina/config"

--for only reading the props from files
 profiles:
    active: native
  cloud:
    config:
      server:
        native:
          search-locations: "classpath:/config"
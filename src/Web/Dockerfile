#I DONT KNOW WHAT IM DOING
#https://www.twilio.com/blog/2017/03/deploy-net-core-with-docker-and-now-sh.html
FROM microsoft/aspnetcore
MAINTAINER Kevin Turkington "Turkingk@oregonstate.edu"

LABEL name "docker-example"

WORKDIR /app
COPY out .

ENV ASPNETCORE_URLS http://*:5000
EXPOSE 5000
	
ENTRYPOINT ["dotnet",  "docker-example.dll"]






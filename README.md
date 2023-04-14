# lame_lib_publishing
I am archiving this repo, this was used to publish to a Jfrog Artifactory instance. That worked, but Jfrog requires you to use the instance every 30 days or they turn it off. I started publishingto maven central instead. - Dan April 2023

Need to local publish https://github.com/nwaldispuehl/java-lame for use

I currently just built the library on my own machine then uploaded to artifactory. https://daberkow.jfrog.io/artifactory/daberkow/net/sourceforge/lame/java-lame-3.98.4.jar

curl --silent --show-error --fail --user "${ARTIFACTORY_USERNAME}:${ARTIFACTORY_PASSWORD}" --request PUT "https://daberkow.jfrog.io/artifactory/daberkow/net/sourceforge/lame/java-lame-3.98.4.jar" --upload-file ./java-lame-3.98.4.jar

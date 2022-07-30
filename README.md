# lame_lib_publishing
Need to local publish https://github.com/nwaldispuehl/java-lame for use

I currently just built the library on my own machine then uploaded to artifactory. https://daberkow.jfrog.io/artifactory/daberkow/net/sourceforge/lame/java-lame-3.98.4.jar

curl --silent --show-error --fail --user "${ARTIFACTORY_USERNAME}:${ARTIFACTORY_PASSWORD}" --request PUT "https://daberkow.jfrog.io/artifactory/daberkow/net/sourceforge/lame/java-lame-3.98.4.jar" --upload-file ./java-lame-3.98.4.jar

## Installation
```
# Install dependencies
sudo apt-get install libraptor2-0 python-librdf python-jpype
sudo pip install neo4j-embedded

# Set the JAVA_HOME path it isn't set
export JAVA_HOME=/usr/lib/jvm/java-7-oracle/jre/

# Clone this git repository
git clone git@github.com:tiepologian/dbpediaNeo4j.git
```


## Usage
```
python dbpediaNeo4j.py /path/to/dbpedia/dump.nt
...wait a few hours regarding PCs power...
Progress: 100%
Finished - 25,850,000 relationships imported in 39,820 seconds
```

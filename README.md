# DOES NOT BUILD

Build fails whilst making "ojo"

```sh

make[3]: Entering directory '/home/ross/Downloads/fossology-4.0.0/src/ojo/agent'
OjoAgent.cc: In member function ‘std::vector<ojomatch> OjoAgent::processFile(const std::string&, OjosDatabaseHandler&, int, int)’:
OjoAgent.cc:54:21: error: aggregate ‘std::stringstream sstr’ has incomplete type and cannot be defined
   54 |   std::stringstream sstr;
      |                     ^~~~
OjoAgent.cc: In member function ‘std::vector<ojomatch> OjoAgent::processFile(const std::string&)’:
OjoAgent.cc:88:21: error: aggregate ‘std::stringstream sstr’ has incomplete type and cannot be defined
   88 |   std::stringstream sstr;

```

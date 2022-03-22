# Some files to run and monitor GBC validator

Use [that](https://github.com/gnosischain/prysm-launch.git) repository to start your GBC node, import and run validators. Main `docker-compose.yml` file is taken from there

I slightly modified the `docker-compose.yml` file to enable and expose `/metrics` endpoints. It looks reasonable to merge both docker-compose files into one and put all the services into a common network just to be able to use services' names as DNS names

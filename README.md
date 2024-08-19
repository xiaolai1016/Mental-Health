Install Synthea
Clone the repository
git clone https://github.com/synthetichealth/synthea.git
cd synthea
Build Synthea
./gradlew build check test
Generate Synthetic Data
./run_synthea -p 3000 -m mental_health California

API Automation Framework

Deskripsi project :
Testing menggunakan testing JUnit, dengan HTTP client library menggunakan Request, struktur projek dengan utilities

Library yg digunakan :
testImplementation 'org.junit.jupiter:junit-jupiter-api:5.8.1'
testRuntimeOnly 'org.junit.jupiter:junit-jupiter-engine:5.8.1'
testImplementation 'org.junit.vintage:junit-vintage-engine:5.7.2'
implementation group: 'io.cucumber', name: 'cucumber-java', version: '7.12.0'
testImplementation group: 'io.cucumber', name: 'cucumber-junit', version: '7.12.0'
testImplementation group: 'io.rest-assured', name: 'rest-assured', version: '5.3.0'
testImplementation group: 'org.json', name: 'json', version: '20220924'
testImplementation 'io.rest-assured:json-path:5.3.0'
testImplementation 'io.rest-assured:json-schema-validator:5.3.0'
testImplementation group: 'org.assertj', name: 'assertj-core', version: '3.24.0'

Menjalankan Project :
1. Membuat folder feature cucumber, folder stepDef, folder pages,folder helper, folder runner
2. Membuat gherkin di feature folder
2. Create step definitation 
3. Create function di page class
4. Create function di models class
5. Create function Endpoint, utility class
6. Create function di runner class
7. Convert json to json schema data di liquid.technologies.com
8. Create json schema data file


Appointments Management in Healthcare with DMN
=======================

GET decision model:

http://localhost:8080/kie-server/services/rest/server/containers/Appointments_1.0.0-SNAPSHOT/dmn

POST decision model execution request:

http://localhost:8080/kie-server/services/rest/server/containers/Appointments_1.0.0-SNAPSHOT/dmn
{
    "model-namespace": "https://healthcare.com/dmn/_1D743DD0-BFD7-4EED-9632-D0C7EB79291F",
    "model-name": "Appointments",
    "decision-name": [],
    "decision-id": [],
    "dmn-context": {
    	"today": "2019-10-21",
        "patient has scheduled appointment": true,
        "appointment date": "2019-10-22",
        "patient has used portal": true,
        "patient is admitted": true,
        "patient age": 25,
        "patient is pregnant": false,
        "patient has a disability": true,
        "facility has valet": true
    }
}
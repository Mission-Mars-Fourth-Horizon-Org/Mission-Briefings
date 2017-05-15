# MISSION GOAL : Verify Crew

Our networks are back online and we’ve successfully connected to a webcam on the Mars base, but our mission doesn’t end here. After a period of silence, we need to verify all is well with our team, confirm their identities and ensure we’re not communicating with interlopers.

Your mission is to use the Azure Cognitive Services Face API to detect the faces in this photo, retrieved from a Martian webcam just minutes ago. We must verify that all crew members are present. Any unusual results should be reported immediately to the commanding officers in the room. Let’s jump right in.

____

## CORE SKILL TRAINING

To ensure that you are technically proficient with the Cognitive Services Face API, we ask that you first complete the following core skill's training exercise:

> **Note**: Even if you are working in teams, it is recommended that each team member complete the core skill training exercises.  This will make sure that the entire team is ready to accomplish the Mission Objectives. 

* <a target="_blank" href="https://aka.ms/face-cs">Get Started with Face API in C#</a> (<a target="_blank" href="https://aka.ms/face-cs">https://aka.ms/face-cs</a>)
* <a target="_blank" href="https://aka.ms/face-py">Get Started with Face API in Python Tutorial</a> (<a target="_blank" href="https://aka.ms/face-py">https://aka.ms/face-py</a>)
* <a target="_blank" href="https://aka.ms/face-jv">Getting Started with Face API in Java for Android Tutorial</a> (<a target="_blank" href="https://aka.ms/face-jv">https://aka.ms/face-jv</a>)

____

## MISSION OBJECTIVES

Now that you can successfully interact with the Cognitive Services Face API, your mission is to use an image of the crew from the webcam on Mars to detect the faces and count them off. You need to verify that all six crew members are present and appear healthy. 

In addition, our telemetry is showing some odd data… either our sensors are on the fritz, or there is an additional life form out there with them. The six crew members are listed below and can also be found in your mission dossier:

| Photo | Name | Position | 
| --- | --- | --- |
| ![Anna Malli](images/AnnaMalli.jpg) | Anna Malli | Commander | 
| ![Erika Mustermann](images/ErikaMustermann.jpg) | Erika Mustermann | Mission Specialist |
| ![Ivan Sidorov](images/IvanSidorov.jpg) |Ivan Sidorov | Payload Specialist |
| ![Juan Pérez](images/JuanPerez.jpg) | Juan Pérez | Flight Engineer |
| ![Seán Ó Rudaí](images/SeanORudai.jpg) | Seán Ó Rudaí | Pilot |
| ![Jean Dupont](images/JeanDupont.jpg) | Jean Dupont | Payload Commander |

### To verify the crew status:

1. Use a copy of the photo recently retrieved from the Mars base monitoring camera here: <a target="_blank" href="https://aka.ms/fourthhorizoncrewphoto">Crew Photo</a> (<a target="_blank" href="https://aka.ms/fourthhorizoncrewphoto">https://aka.ms/fourthhorizoncrewphoto</a>)

1. Upload the photo to congitive services using the application you created in the core skills training exercise above.

    > **Note:** if you had problems creating the app above, or just didn't have time, you can use the sample implementation <a target="_blank" href="https://www.microsoft.com/cognitive-services/en-us/face-api">here</a>

1. Count the faces, and verify that all six crew members are present.

1. Look for any additional faces or life forms that may be present.


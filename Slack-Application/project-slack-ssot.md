# Project Title
Mention here the name of the company owning the project and the link to their website.

## Summary and Scope

[Add a brief summary of the project and its scope here.]

The summary should consist of a maximum of three paragraphs or a link to a file containing the project description. It is important to clearly state the challenge of the project and how it will be addressed, as well as the expected outcomes for both the client and Akurey.

Deliverables
Regarding the project scope, it is important to clearly define what Akurey will deliver and what parts are the responsibility of someone else. A link to a document or platform is also acceptable. It is also crucial to outline any potential business opportunities, improvements, and new fields of research that may arise from the project, either for Akurey or the client.

## Client Description

### name of the client

![Client Logo](link_to_client_logo)

- what is the business of the client
- stakeholders

## Concept Map

if its important add a concept map diagram of the project or business.

## Project Folder Structure

![Folder Structure](link_to_image_of_folder_structure)

The folder structure can be divided into frontend, backend, and other categories. If the image is not self-explanatory, please provide clarification bullets for each folder to ensure understanding.

## Architecture Diagram

When required add an architecture diagram of the project here.

## Services and Technical Troubleshooting

- list and explanation of services, servers, drivers required for this project
- Add a list of common technical issues and their troubleshooting steps here.

## Team Members

| Name | Position | Contact Buddy |
| --- | --- | --- |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |

## Requirement

log of requirements changes

* Kafay Ng [2023-04-26T20:53:32.225Z]

Message: Soledad Kopper Kafay Ng ya estoy satisfecho con esta plantila <https://github.com/akurey/aktech/blob/master/project-slack-ssot.md>

Notes: Nuñez shared a link


* Kafay Ng [2023-04-26T21:02:34.915Z]

Message: Claro digamos que tendría este formato

```
* Buenos días, una consulta
Con respecto al update md file se había pensado que tuviera este formato [Wed, 05 Apr 2023 09:11:40] 

[Additional Notes]
```

Algo así, pero queremos guardar de quien fue la propuesta? o quien mando el update?
O simplemente que se vaya agregando y ya? :thinking_face:  Lo digo en caso de que se quiera saber quien fue el que hizo la propuesta o hizo push al md file

Notes: New Requirem
#### **Kafay Ng [2023-04-27T20:40:12.121Z]**

Message: Buenas tardes, unas notas sobre la reu que acabamos de tener entre Rodrigo Nunez y yo
• Manejo de token para git: se va a utilizar el método de crear un token con un usuario nuevo (dependiendo del cliente) o que un integrante creé el token. Este token tiene la posibilidad de no experirar entonces quedará a disposición del proyecto/cliente
• Manejo de los repositorios: los repositorios van a tener únicamente los md files del proyecto con la información (scopes, requirements, teams, etc…) por lo que se van a clonar los repositorios a nivel de codigo y se van a mantener en memoria en vez de borrarlos una vez terminado el proceso de edición -&gt; git add -&gt; git commit -&gt; git push -&gt; merge
• Buscar un módulo para la escritura de archivos que maneje la inserción en lugares específicos de un archivo para poder evitar tener un buffer de un antes del string a insertar y un después del string a insertar y hacerles join a un solo string grande
* Kafay Ng [2023-04-27T20:59:08.046Z]

Message: <https://github.com/akurey/AK-Slack-App/blob/main/README.md>

Notes: Update

#### **Kafay Ng [2023-05-11T16:41:34.311Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:


#### **Kafay Ng [2023-05-11T17:03:45.624Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Marcela's Ad

#### **Kafay Ng [2023-05-11T17:25:10.300Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T17:31:04.495Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's announcement regarding fofo

#### **Kafay Ng [2023-05-11T17:35:19.784Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T17:37:32.673Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T18:48:09.629Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation to fofo coming to CR

#### **Kafay Ng [2023-05-11T20:37:53.756Z]** 

Message: Buenos días, bastante bien
Veo que podemos hacer el bypass del validation que le comente ayer con el token ya generado, hoy me estoy dedicando a ya mover toda la implementación de nodegit a octokit que es lo que se usa el github api

Notes: Kafa'ys update about slack app
Push sent  at: 2:37pm

#### **Kafay Ng [2023-05-11T20:45:47.738Z]** 

Message: Lo que pasa es que la versión con la que se está haciendo build localmente está diseñado para esa arquitectura pero cuando se sube a serverless, tiene otra arquitectura, entonces  lo que me dijo Fer es que se tendría que instalar el cli al serverless para que funcione porque se está usando el modulo nodegit para la escritura, igual estoy esperando a ver que me dice Bryan  porque puede que él tenga otro approach

Notes: Sol's update about slack app issue
Push sent  at: 2:45pm

#### **Kafay Ng [2023-05-11T20:54:21.923Z]** 

Message: Pero por alguna razón pareciera que mi token de git expira, entonces ahorita en unos 5mn les hago otro spam

Notes: Update at 2:54pm

#### **Jose Andrés Barboza González [2023-05-12T20:34:03.624Z]** 

Message: cat

Notes: Holi

#### **Ixel Castro Richard [2023-05-12T20:41:42.226Z]** 

Message: Slack procesa por eventos de clicks a diferentes componentes y no por form
Entonces lo que esta pasando es que ahí hubo un post de evento tipo dropdown y select que en realidad no nos sirve pero slack siempre lo envia como evento, el error es que no se esta haciendo nada con ese evento

Notes: Update

#### **Ixel Castro Richard [2023-05-12T21:28:46.650Z]** 

Message: <https://github.com/akurey/AK-Slack-App#add-akurey-source-application-to-the-channels-on-slack>

Notes: Update

#### **Kafay Ng [2023-05-16T20:23:59.201Z]** 

Message: Hello everyone! We are collecting money for our first face-to-face volunteering of the year :moneybag: Help us bring color to Fundación Bandera Blanca by contributing to our campaign for painting materials.
We need 100,000 colones to buy all the materials. If you want to contribute please do a *sinpe movil* to the number *8765-4392*  with your name and the word “volunteer” for example, Wong-Volunteer.
Thank you very much :blue_heart:

“hands that give will never be empty :joy:”

Notes: Test image link

#### **Kafay Ng [2023-05-16T22:55:34.156Z]** 

Message: Hello everyone! We are collecting money for our first face-to-face volunteering of the year :moneybag: Help us bring color to Fundación Bandera Blanca by contributing to our campaign for painting materials.
We need 100,000 colones to buy all the materials. If you want to contribute please do a *sinpe movil* to the number *8765-4392*  with your name and the word “volunteer” for example, Wong-Volunteer.
Thank you very much :blue_heart:

“hands that give will never be empty :joy:”

Notes: Sent through IOS

#### **Kafay Ng [2023-05-17T14:55:18.902Z]** 

Message: GM! Sorry I couldn't  join:disappointed:
 :hourglass:️ Y: I was working on Patch, post and put method, I also saw some features about Azure and its cloud
 :hourglass_flowing_sand: T: I'll work on authentication methods and also 3rd party integration (understanding how it works), continue to look at Azure services and pick up the animal project tasks
 :no_entry_sign: B: None

Notes: QA Channel testing

#### **Kafay Ng [2023-05-17T14:56:05.228Z]** 

Message: GM! Sorry I couldn't  join:disappointed:
 :hourglass:️ Y: I was working on Patch, post and put method, I also saw some features about Azure and its cloud
 :hourglass_flowing_sand: T: I'll work on authentication methods and also 3rd party integration (understanding how it works), continue to look at Azure services and pick up the animal project tasks
 :no_entry_sign: B: None

Notes: QA Channel testing2

## Technical

log of technical decisions

#### **Kafay Ng [2023-05-11T18:39:14.484Z]** 

Message: Estoy viendo que no llega, hace el update al git pero no manda el mensaje
Pero estoy viendo que podría ser un issue con lambda <https://github.com/slackapi/bolt-js/issues/1299>
Pero que hay alternativas como lazyloading

Notes: Kafay's issue

#### **Kafay Ng [2023-05-11T18:42:27.747Z]** 

Message: Cree estos dos tickets <https://ak-slack-app.atlassian.net/browse/ASA-51> y <https://ak-slack-app.atlassian.net/browse/ASA-50> (este ya tiene MR)

Notes: Kafay's MRs

#### **Kafay Ng [2023-05-11T18:58:25.367Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T19:00:46.304Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T19:03:31.476Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation

#### **Kafay Ng [2023-05-11T19:11:42.413Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Marcela's Update

#### **Kafay Ng [2023-05-11T19:22:20.105Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:23:17.308Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:28:34.875Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:38:50.110Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T20:07:08.770Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T20:23:27.830Z]** 

Message: Buenos días, bastante bien
Veo que podemos hacer el bypass del validation que le comente ayer con el token ya generado, hoy me estoy dedicando a ya mover toda la implementación de nodegit a octokit que es lo que se usa el github api

Notes: update

#### **Kafay Ng [2023-05-12T16:17:48.674Z]** 

Message: GM!
 :hourglass:️ Y: reviewing FWD program
 :hourglass_flowing_sand: T: Reviewing FWD program, 1:1 and I'll be off the afternoon
 :no_entry_sign: B: None


#### **Kafay Ng [2023-05-12T16:39:49.441Z]** 

Message: Hola, Kafay, todo bien?
Sol me mandó a hablar con usted para que me ayudara con cómo voy a testear la app de Slack en la que estaban trabajando

Notes: Update test

#### **Ixel Castro Richard [2023-05-12T20:11:17.877Z]** 
Notes: Correct way of getting notifications

#### **Ixel Castro Richard [2023-05-12T20:32:14.006Z]** 

Message: Slack procesa por eventos de clicks a diferentes componentes y no por form
Entonces lo que esta pasando es que ahí hubo un post de evento tipo dropdown y select que en realidad no nos sirve pero slack siempre lo envia como evento, el error es que no se esta haciendo nada con ese evento

Notes: Technical Issue

#### **Rodrigo Nunez [2023-05-12T21:23:53.810Z]** 

Message: Hola buenos días, para ya probarlos con otros proyectos sería modificar el data.json que esta en el repo y si se quiere que el chatbot mande mensajes a channels se tiene que agregar a los channels. En el readme esta más información de como hacerle setup


#### **Kafay Ng [2023-05-15T17:41:02.147Z]** 

Message: Recordé que tenemos el alias que se creo para aws <mailto:slack-poc-aws@akurey.com|slack-poc-aws@akurey.com>


#### **Kafay Ng [2023-05-15T17:52:08.983Z]** 

Message: GM! Sorry I couldn't, had another meeting
 :hourglass:️ Y: Demo and reviewing the program
 :hourglass_flowing_sand: T: I'll be having a couple of meetings during the morning then I'll continue reviewing the program and creating some figma files for the course
 :no_entry_sign: B: None

Notes: Status Update

#### **Kafay Ng [2023-05-16T14:36:20.188Z]** 

Message: <https://files.slack.com/files-tmb/T2DPLE8AY-F0588PY7N3A-307b69ec49/internal_message_64.png>

Notes: TEST QA

#### **Kafay Ng [2023-05-16T14:41:30.197Z]** 

Message: GM! Sorry I couldn't, had another meeting
 :hourglass:️ Y: Demo and reviewing the program
 :hourglass_flowing_sand: T: I'll be having a couple of meetings during the morning then I'll continue reviewing the program and creating some figma files for the course
 :no_entry_sign: B: None

Notes: TEST Prod

#### **Kafay Ng [2023-05-16T21:31:58.339Z]** 

Message: nada mas sad que un restaurante que uno recomienda quede mal


#### **Kafay Ng [2023-05-16T21:35:55.427Z]** 

Message: Configuraste el aws config?


#### **Kafay Ng [2023-05-16T21:36:29.288Z]** 

Message: Configuraste el aws config?


#### **Kafay Ng [2023-05-16T21:38:45.668Z]** 

Message: Configuraste el aws config?


#### **Ixel Castro Richard [2023-05-16T21:39:09.284Z]** 

Message: Slack Test

Notes: Update

#### **Kafay Ng [2023-05-16T21:48:49.015Z]** 

Message: Y a mí me llegan las notificaciones, pero al channel no


#### **Kafay Ng [2023-05-16T21:51:18.166Z]** 

Message: sabe como loggear usando el aws cli?


#### **Kafay Ng [2023-05-16T21:54:11.980Z]** 

Message: I've found this site that might be useful for some of you :stuck_out_tongue: <https://endoflife.date/python>


#### **Kafay Ng [2023-05-16T21:55:45.198Z]** 

Message: Lo puedo reemplazar por otro que no tiene el listener pero se vería así, con el label arriba en vez de que sea al lado


#### **Kafay Ng [2023-05-16T21:57:40.286Z]** 

Message: Lo puedo reemplazar por otro que no tiene el listener pero se vería así, con el label arriba en vez de que sea al lado


#### **Kafay Ng [2023-05-16T22:00:24.458Z]** 

Message: Hello everyone! We are collecting money for our first face-to-face volunteering of the year :moneybag: Help us bring color to Fundación Bandera Blanca by contributing to our campaign for painting materials.
We need 100,000 colones to buy all the materials. If you want to contribute please do a *sinpe movil* to the number *8765-4392*  with your name and the word “volunteer” for example, Wong-Volunteer.
Thank you very much :blue_heart:

“hands that give will never be empty :joy:”


#### **Kafay Ng [2023-05-16T22:02:56.022Z]** 

Message: Ya vi lo que pasa en mobile, el no agarra valores
Voy a tirar primero ese update del form a un ticket que voy a crear


#### **Kafay Ng [2023-05-16T22:18:53.902Z]** 

Message: Te aviso cuando se haga merge de ese ticket, y vos le haces el merge local?
Para no tirar yo el deploy con mi `data.json` diferente al tuyo


#### **Kafay Ng [2023-05-16T22:24:22.952Z]** 

Message: Hola 


#### **Kafay Ng [2023-05-16T22:56:04.196Z]** 

Message: Hello everyone! We are collecting money for our first face-to-face volunteering of the year :moneybag: Help us bring color to Fundación Bandera Blanca by contributing to our campaign for painting materials.
We need 100,000 colones to buy all the materials. If you want to contribute please do a *sinpe movil* to the number *8765-4392*  with your name and the word “volunteer” for example, Wong-Volunteer.
Thank you very much :blue_heart:

“hands that give will never be empty :joy:”

Notes: Sent through IOS

#### **Ixel Castro Richard [2023-05-17T00:45:28.929Z]** 

Message: Slack Test

Notes: Update

#### **Kafay Ng [2023-05-17T04:43:24.623Z]** 

Message: fallback text, check update in SSOTFile


#### **Kafay Ng [2023-05-17T14:57:28.980Z]** 

Message: GM! Sorry I couldn't  join:disappointed:
 :hourglass:️ Y: I was working on Patch, post and put method, I also saw some features about Azure and its cloud
 :hourglass_flowing_sand: T: I'll work on authentication methods and also 3rd party integration (understanding how it works), continue to look at Azure services and pick up the animal project tasks
 :no_entry_sign: B: None

Notes: QA Channel testing3

#### **Kafay Ng [2023-05-17T15:04:22.841Z]** 

Message: Hello everyone, I hope you're having a good Tuesday :heart_hands::skin-tone-2:
I wanted to let you know that we have started collecting money for the materials for the volunteer activity :waving_white_flag:
So far, we have gathered *21,000 colones* :cry: *but we need to reach 100,000 colones.* If you would like to contribute, please make a SINPE to 8765-4392 with your name and the word "volunteer," for example, "Montse-volunteer."

Thank you for your support :blue_heart:

Notes: Announcement made!

#### **Kafay Ng [2023-05-17T15:06:51.443Z]** 

Message: Hello everyone, I hope you're having a good Tuesday :heart_hands::skin-tone-2:
I wanted to let you know that we have started collecting money for the materials for the volunteer activity :waving_white_flag:
So far, we have gathered *21,000 colones* :cry: *but we need to reach 100,000 colones.* If you would like to contribute, please make a SINPE to 8765-4392 with your name and the word "volunteer," for example, "Montse-volunteer."

Thank you for your support :blue_heart:

Notes: Announcement Made!

#### **Kafay Ng [2023-05-17T18:21:58.221Z]** 

Message: Sip, desde mobile debería de funcionar

Notes: Test new form

#### **Rodrigo Nunez [2023-05-17T20:17:25.783Z]** 

Message: me gustaría que veas un videito que hizo fabri hace tiempo, tal vez no aplica directamente a vos pero velo pues si el día de mañana ves que alguién pifia mucho a nivel de git y control de versiones o tiene que aprender o algo así, lo pongas a ver este video o podas sugerirle algo

Notes: este texto es opcional , este es un demo con joselying

#### **Kafay Ng [2023-05-18T16:44:37.397Z]** 

Message: Miércoles de couture :sparkles: :fried_egg: :sparkles: 

Notes: Y ahora?

#### **Kafay Ng [2023-05-18T16:46:58.679Z]** 

Message: Voy de una molestando.
despues de instalar el Backup de la base de dato al hacer click en el nombre de la base "localhost" para hacer login ,
la consola me tira este error :thinking_face:  no se si alguno ha visto algo parecido , es de rest_partner

Notes: Este?

#### **Kafay Ng [2023-05-18T16:51:23.177Z]** 

Message: Voy de una molestando.
despues de instalar el Backup de la base de dato al hacer click en el nombre de la base "localhost" para hacer login ,
la consola me tira este error :thinking_face:  no se si alguno ha visto algo parecido , es de rest_partner


#### **Kafay Ng [2023-05-18T16:51:53.698Z]** 

Message: Voy de una molestando.
despues de instalar el Backup de la base de dato al hacer click en el nombre de la base "localhost" para hacer login ,
la consola me tira este error :thinking_face:  no se si alguno ha visto algo parecido , es de rest_partner


#### **Kafay Ng [2023-05-18T17:16:07.226Z]** 

Message: Miércoles de couture :sparkles: :fried_egg: :sparkles: 


PCFET0NUWVBFIGh0bWw+PGh0bWwgbGFuZz0iZW4tVVMiIGNsYXNzPSIiIGRhdGEtcHJpbWVyPjxoZWFkPjxsaW5rIGhyZWY9Imh0dHBzOi8vYS5zbGFjay1lZGdlLmNvbS9kNWZiYTRjL21hcmtldGluZy9zdHlsZS9vbmV0cnVzdC9vbmV0cnVzdF9iYW5uZXIuY3NzIiByZWw9InN0eWxlc2hlZXQiIHR5cGU9InRleHQvY3NzIiBvbmxvYWQ9IndpbmRvdy5fY2RuID8gX2Nkbi5vayh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgb25lcnJvcj0id2luZG93Ll9jZG4gPyBfY2RuLmZhaWxlZCh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgY3Jvc3NvcmlnaW49ImFub255bW91cyI+PGxpbmsgaHJlZj0iaHR0cHM6Ly9hLnNsYWNrLWVkZ2UuY29tL2UwNjQ1MWEvc3R5bGUvbGlicy9sYXRvLTItY29tcHJlc3NlZC5jc3MiIHJlbD0ic3R5bGVzaGVldCIgdHlwZT0idGV4dC9jc3MiIG9ubG9hZD0id2luZG93Ll9jZG4gPyBfY2RuLm9rKHRoaXMsIGFyZ3VtZW50cykgOiBudWxsIiBvbmVycm9yPSJ3aW5kb3cuX2NkbiA/IF9jZG4uZmFpbGVkKHRoaXMsIGFyZ3VtZW50cykgOiBudWxsIiBjcm9zc29yaWdpbj0iYW5vbnltb3VzIj48bGluayBocmVmPSJodHRwczovL2Euc2xhY2stZWRnZS5jb20vY3NzL3Y1L3N0eWxlL19nZW5lcmljLnR5cG9ncmFwaHkubGFyc3NlaXQuODVhZDBlMGJiZTYxYmRiZjYyYmRkOWVmYTE1YTkyMWUwMTAzM2MzNy5jc3MiIHJlbD0ic3R5bGVzaGVldCIgdHlwZT0idGV4dC9jc3MiIG9ubG9hZD0id2luZG93Ll9jZG4gPyBfY2RuLm9rKHRoaXMsIGFyZ3VtZW50cykgOiBudWxsIiBvbmVycm9yPSJ3aW5kb3cuX2NkbiA/IF9jZG4uZmFpbGVkKHRoaXMsIGFyZ3VtZW50cykgOiBudWxsIiBjcm9zc29yaWdpbj0iYW5vbnltb3VzIj48bGluayByZWw9ImNhbm9uaWNhbCIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20iPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJlbi11cyIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20iPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJlbi1hdSIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC9lbi1hdSI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9ImVuLWdiIiBocmVmPSJodHRwczovL3NsYWNrLmNvbS9pbnRsL2VuLWdiIj4KCjxsaW5rIHJlbD0iYWx0ZXJuYXRlIiBocmVmbGFuZz0iZW4taW4iIGhyZWY9Imh0dHBzOi8vc2xhY2suY29tL2ludGwvZW4taW4iPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJmci1jYSIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC9mci1jYSI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9ImZyLWZyIiBocmVmPSJodHRwczovL3NsYWNrLmNvbS9pbnRsL2ZyLWZyIj4KCjxsaW5rIHJlbD0iYWx0ZXJuYXRlIiBocmVmbGFuZz0iZGUtZGUiIGhyZWY9Imh0dHBzOi8vc2xhY2suY29tL2ludGwvZGUtZGUiPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJlcy1lcyIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC9lcy1lcyI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9ImVzLTQxOSIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC9lcy1sYSI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9ImphLWpwIiBocmVmPSJodHRwczovL3NsYWNrLmNvbS9pbnRsL2phLWpwIj4KCjxsaW5rIHJlbD0iYWx0ZXJuYXRlIiBocmVmbGFuZz0icHQtYnIiIGhyZWY9Imh0dHBzOi8vc2xhY2suY29tL2ludGwvcHQtYnIiPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJrby1rciIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC9rby1rciI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9Iml0LWl0IiBocmVmPSJodHRwczovL3NsYWNrLmNvbS9pbnRsL2l0LWl0Ij4KCjxsaW5rIHJlbD0iYWx0ZXJuYXRlIiBocmVmbGFuZz0iemgtY24iIGhyZWY9Imh0dHBzOi8vc2xhY2suY29tL2ludGwvemgtY24iPgoKPGxpbmsgcmVsPSJhbHRlcm5hdGUiIGhyZWZsYW5nPSJ6aC10dyIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20vaW50bC96aC10dyI+Cgo8bGluayByZWw9ImFsdGVybmF0ZSIgaHJlZmxhbmc9IngtZGVmYXVsdCIgaHJlZj0iaHR0cHM6Ly9zbGFjay5jb20iPgoKPHNjcmlwdD53aW5kb3cudHNfZW5kcG9pbnRfdXJsID0gImh0dHBzOlwvXC9zbGFjay5jb21cL2JlYWNvblwvdGltaW5nIjsoZnVuY3Rpb24oZSkgewoJdmFyIG49RGF0ZS5ub3c/RGF0ZS5ub3coKTorbmV3IERhdGUscj1lLnBlcmZvcm1hbmNlfHx7fSx0PVtdLGE9e30saT1mdW5jdGlvbihlLG4pe2Zvcih2YXIgcj0wLGE9dC5sZW5ndGgsaT1bXTthPnI7cisrKXRbcl1bZV09PW4mJmkucHVzaCh0W3JdKTtyZXR1cm4gaX0sbz1mdW5jdGlvbihlLG4pe2Zvcih2YXIgcixhPXQubGVuZ3RoO2EtLTspcj10W2FdLHIuZW50cnlUeXBlIT1lfHx2b2lkIDAhPT1uJiZyLm5hbWUhPW58fHQuc3BsaWNlKGEsMSl9O3Iubm93fHwoci5ub3c9ci53ZWJraXROb3d8fHIubW96Tm93fHxyLm1zTm93fHxmdW5jdGlvbigpe3JldHVybihEYXRlLm5vdz9EYXRlLm5vdygpOituZXcgRGF0ZSktbn0pLHIubWFya3x8KHIubWFyaz1yLndlYmtpdE1hcmt8fGZ1bmN0aW9uKGUpe3ZhciBuPXtuYW1lOmUsZW50cnlUeXBlOiJtYXJrIixzdGFydFRpbWU6ci5ub3coKSxkdXJhdGlvbjowfTt0LnB1c2gobiksYVtlXT1ufSksci5tZWFzdXJlfHwoci5tZWFzdXJlPXIud2Via2l0TWVhc3VyZXx8ZnVuY3Rpb24oZSxuLHIpe249YVtuXS5zdGFydFRpbWUscj1hW3JdLnN0YXJ0VGltZSx0LnB1c2goe25hbWU6ZSxlbnRyeVR5cGU6Im1lYXN1cmUiLHN0YXJ0VGltZTpuLGR1cmF0aW9uOnItbn0pfSksci5nZXRFbnRyaWVzQnlUeXBlfHwoci5nZXRFbnRyaWVzQnlUeXBlPXIud2Via2l0R2V0RW50cmllc0J5VHlwZXx8ZnVuY3Rpb24oZSl7cmV0dXJuIGkoImVudHJ5VHlwZSIsZSl9KSxyLmdldEVudHJpZXNCeU5hbWV8fChyLmdldEVudHJpZXNCeU5hbWU9ci53ZWJraXRHZXRFbnRyaWVzQnlOYW1lfHxmdW5jdGlvbihlKXtyZXR1cm4gaSgibmFtZSIsZSl9KSxyLmNsZWFyTWFya3N8fChyLmNsZWFyTWFya3M9ci53ZWJraXRDbGVhck1hcmtzfHxmdW5jdGlvbihlKXtvKCJtYXJrIixlKX0pLHIuY2xlYXJNZWFzdXJlc3x8KHIuY2xlYXJNZWFzdXJlcz1yLndlYmtpdENsZWFyTWVhc3VyZXN8fGZ1bmN0aW9uKGUpe28oIm1lYXN1cmUiLGUpfSksZS5wZXJmb3JtYW5jZT1yLCJmdW5jdGlvbiI9PXR5cGVvZiBkZWZpbmUmJihkZWZpbmUuYW1kfHxkZWZpbmUuYWpzKSYmZGVmaW5lKCJwZXJmb3JtYW5jZSIsW10sZnVuY3Rpb24oKXtyZXR1cm4gcn0pIC8vIGVzbGludC1kaXNhYmxlLWxpbmUKfSkod2luZG93KTs8L3NjcmlwdD48c2NyaXB0PgoKKGZ1bmN0aW9uICgpIHsKCQoJd2luZG93LlRTTWFyayA9IGZ1bmN0aW9uIChtYXJrX2xhYmVsKSB7CgkJaWYgKCF3aW5kb3cucGVyZm9ybWFuY2UgfHwgIXdpbmRvdy5wZXJmb3JtYW5jZS5tYXJrKSByZXR1cm47CgkJcGVyZm9ybWFuY2UubWFyayhtYXJrX2xhYmVsKTsKCX07Cgl3aW5kb3cuVFNNYXJrKCdzdGFydF9sb2FkJyk7CgoJCgl3aW5kb3cuVFNNZWFzdXJlQW5kQmVhY29uID0gZnVuY3Rpb24gKG1lYXN1cmVfbGFiZWwsIHN0YXJ0X21hcmtfbGFiZWwpIHsKCQlpZiAoIXdpbmRvdy5wZXJmb3JtYW5jZSB8fCAhd2luZG93LnBlcmZvcm1hbmNlLm1hcmsgfHwgIXdpbmRvdy5wZXJmb3JtYW5jZS5tZWFzdXJlKSB7CgkJCXJldHVybjsKCQl9CgoJCXBlcmZvcm1hbmNlLm1hcmsoc3RhcnRfbWFya19sYWJlbCArICdfZW5kJyk7CgoJCXRyeSB7CgkJCXBlcmZvcm1hbmNlLm1lYXN1cmUobWVhc3VyZV9sYWJlbCwgc3RhcnRfbWFya19sYWJlbCwgc3RhcnRfbWFya19sYWJlbCArICdfZW5kJyk7CgkJCXdpbmRvdy5UU0JlYWNvbihtZWFzdXJlX2xhYmVsLCBwZXJmb3JtYW5jZS5nZXRFbnRyaWVzQnlOYW1lKG1lYXN1cmVfbGFiZWwpWzBdLmR1cmF0aW9uKTsKCQl9IGNhdGNoIChlKSB7CgkJCQoJCX0KCX07CgoJCglpZiAoJ3NlbmRCZWFjb24nIGluIG5hdmlnYXRvcikgewoJCXdpbmRvdy5UU0JlYWNvbiA9IGZ1bmN0aW9uIChsYWJlbCwgdmFsdWUpIHsKCQkJdmFyIGVuZHBvaW50X3VybCA9IHdpbmRvdy50c19lbmRwb2ludF91cmwgfHwgJ2h0dHBzOi8vc2xhY2suY29tL2JlYWNvbi90aW1pbmcnOwoJCQluYXZpZ2F0b3Iuc2VuZEJlYWNvbigKCQkJCWVuZHBvaW50X3VybCArICc/ZGF0YT0nICsgZW5jb2RlVVJJQ29tcG9uZW50KGxhYmVsICsgJzonICsgdmFsdWUpLAoJCQkJJycKCQkJKTsKCQl9OwoJfSBlbHNlIHsKCQl3aW5kb3cuVFNCZWFjb24gPSBmdW5jdGlvbiAobGFiZWwsIHZhbHVlKSB7CgkJCXZhciBlbmRwb2ludF91cmwgPSB3aW5kb3cudHNfZW5kcG9pbnRfdXJsIHx8ICdodHRwczovL3NsYWNrLmNvbS9iZWFjb24vdGltaW5nJzsKCQkJbmV3IEltYWdlKCkuc3JjID0gZW5kcG9pbnRfdXJsICsgJz9kYXRhPScgKyBlbmNvZGVVUklDb21wb25lbnQobGFiZWwgKyAnOicgKyB2YWx1ZSk7CgkJfTsKCX0KfSkoKTsKPC9zY3JpcHQ+PHNjcmlwdD53aW5kb3cuVFNNYXJrKCdzdGVwX2xvYWQnKTs8L3NjcmlwdD48c2NyaXB0PgooZnVuY3Rpb24gKCkgewoJZnVuY3Rpb24gdGhyb3R0bGUoY2FsbGJhY2ssIGludGVydmFsTXMpIHsKCQl2YXIgd2FpdCA9IGZhbHNlOwoKCQlyZXR1cm4gZnVuY3Rpb24gKCkgewoJCQlpZiAoIXdhaXQpIHsKCQkJCWNhbGxiYWNrLmFwcGx5KG51bGwsIGFyZ3VtZW50cyk7CgkJCQl3YWl0ID0gdHJ1ZTsKCQkJCXNldFRpbWVvdXQoZnVuY3Rpb24gKCkgewoJCQkJCXdhaXQgPSBmYWxzZTsKCQkJCX0sIGludGVydmFsTXMpOwoJCQl9CgkJfTsKCX0KCglmdW5jdGlvbiBnZXRHZW5lcmljTG9nZ2VyKCkgewoJCXJldHVybiB7CgkJCXdhcm46IChtc2cpID0+IHsKCQkJCQoJCQkJaWYgKHdpbmRvdy5jb25zb2xlICYmIGNvbnNvbGUud2FybikgcmV0dXJuIGNvbnNvbGUud2Fybihtc2cpOwoJCQl9LAoJCQllcnJvcjogKG1zZykgPT4gewoJCQkJaWYgKCFtc2cpIHJldHVybjsKCgkJCQlpZiAod2luZG93LlRTQmVhY29uKSByZXR1cm4gd2luZG93LlRTQmVhY29uKG1zZywgMSk7CgoJCQkJCgkJCQlpZiAod2luZG93LmNvbnNvbGUgJiYgY29uc29sZS53YXJuKSByZXR1cm4gY29uc29sZS53YXJuKG1zZyk7CgkJCX0sCgkJfTsKCX0KCglmdW5jdGlvbiBnbG9iYWxFcnJvckhhbmRsZXIoZXZ0KSB7CgkJaWYgKCFldnQpIHJldHVybjsKCgkJCgkJdmFyIGRldGFpbHMgPSAnJzsKCgkJdmFyIG5vZGUgPSBldnQuc3JjRWxlbWVudCB8fCBldnQudGFyZ2V0OwoKCQl2YXIgZ2VuZXJpY0xvZ2dlciA9IGdldEdlbmVyaWNMb2dnZXIoKTsKCgkJCgkJCgkJCgkJCgkJaWYgKG5vZGUgJiYgbm9kZS5ub2RlTmFtZSkgewoJCQl2YXIgbm9kZVNyYyA9ICcnOwoJCQlpZiAobm9kZS5ub2RlTmFtZSA9PT0gJ1NDUklQVCcpIHsKCQkJCW5vZGVTcmMgPSBub2RlLnNyYyB8fCAndW5rbm93bic7CgkJCQl2YXIgZXJyb3JUeXBlID0gZXZ0LnR5cGUgfHwgJ2Vycm9yJzsKCgkJCQkKCQkJCWRldGFpbHMgPSBgWyR7ZXJyb3JUeXBlfV0gZnJvbSBzY3JpcHQgYXQgJHtub2RlU3JjfSAoZmFpbGVkIHRvIGxvYWQ/KWA7CgkJCX0gZWxzZSBpZiAobm9kZS5ub2RlTmFtZSA9PT0gJ0lNRycpIHsKCQkJCW5vZGVTcmMgPSBub2RlLnNyYyB8fCBub2RlLmN1cnJlbnRTcmM7CgoJCQkJZ2VuZXJpY0xvZ2dlci53YXJuKGA8aW1nPiBmaXJlZCBlcnJvciB3aXRoIHVybCA9ICR7bm9kZVNyY31gKTsKCQkJCXJldHVybjsKCQkJfQoJCX0KCgkJCgkJaWYgKGV2dC5lcnJvciAmJiBldnQuZXJyb3Iuc3RhY2spIHsKCQkJZGV0YWlscyArPSBgICR7ZXZ0LmVycm9yLnN0YWNrfWA7CgkJfQoKCQlpZiAoZXZ0LmZpbGVuYW1lKSB7CgkJCQoJCQl2YXIgZmlsZU5hbWUgPSBldnQuZmlsZW5hbWU7CgkJCXZhciBsaW5lTm8gPSBldnQubGluZW5vOwoJCQl2YXIgY29sTm8gPSBldnQuY29sbm87CgoJCQlkZXRhaWxzICs9IGAgZnJvbSAke2ZpbGVOYW1lfWA7CgoJCQkKCQkJaWYgKGxpbmVObykgewoJCQkJZGV0YWlscyArPSBgIEAgbGluZSAke2xpbmVOb30sIGNvbCAke2NvbE5vfWA7CgkJCX0KCQl9CgoJCXZhciBtc2c7CgoJCQoJCWlmIChldnQuZXJyb3IgJiYgZXZ0LmVycm9yLnN0YWNrKSB7CgkJCQoJCQltc2cgPSBkZXRhaWxzOwoJCX0gZWxzZSB7CgkJCQoJCQltc2cgPSBgJHtldnQubWVzc2FnZSB8fCAnJ30gJHtkZXRhaWxzfWA7CgkJfQoKCQkKCQlpZiAobXNnICYmIG1zZy5yZXBsYWNlKSBtc2cgPSBtc2cucmVwbGFjZSgvXHMrL2csICcgJykudHJpbSgpOwoKCQlpZiAoIW1zZyB8fCAhbXNnLmxlbmd0aCkgewoJCQlpZiAobm9kZSkgewoJCQkJdmFyIG5vZGVOYW1lID0gbm9kZS5ub2RlTmFtZSB8fCAndW5rbm93bic7CgoJCQkJCgkJCQkKCQkJCQoJCQkJaWYgKG5vZGVOYW1lID09PSAnVklERU8nKSB7CgkJCQkJcmV0dXJuOwoJCQkJfQoKCQkJCW1zZyA9IGBlcnJvciBldmVudCBmcm9tIG5vZGUgb2YgJHtub2RlTmFtZX0sIG5vIG1lc3NhZ2UgcHJvdmlkZWQ/YDsKCQkJfSBlbHNlIHsKCQkJCW1zZyA9ICdlcnJvciBldmVudCBmaXJlZCwgbm8gcmVsZXZhbnQgbWVzc2FnZSBvciBub2RlIGZvdW5kJzsKCQkJfQoJCX0KCgkJdmFyIGxvZ1ByZWZpeCA9ICdFUlJPUiBjYXVnaHQgaW4ganMvaW5saW5lL3JlZ2lzdGVyX2dsb2JhbF9lcnJvcl9oYW5kbGVyJzsKCgkJbXNnID0gYCR7bG9nUHJlZml4fSAtICR7bXNnfWA7CgoJCWdlbmVyaWNMb2dnZXIuZXJyb3IobXNnKTsKCX0KCgkKCQoJCgl2YXIgY2FwdHVyZSA9IHRydWU7CgoJCgl2YXIgdGhyb3R0bGVkSGFuZGxlciA9IHRocm90dGxlKGdsb2JhbEVycm9ySGFuZGxlciwgMTAwMDApOwoKCXdpbmRvdy5hZGRFdmVudExpc3RlbmVyKCdlcnJvcicsIHRocm90dGxlZEhhbmRsZXIsIGNhcHR1cmUpOwp9KSgpOwo8L3NjcmlwdD48c2NyaXB0IHR5cGU9InRleHQvamF2YXNjcmlwdCIgY3Jvc3NvcmlnaW49ImFub255bW91cyIgc3JjPSJodHRwczovL2Euc2xhY2stZWRnZS5jb20vYnYxLTEwL21hbmlmZXN0LmIwMzkzMTAucHJpbWVyLm1pbi5qcyIgb25sb2FkPSJ3aW5kb3cuX2NkbiA/IF9jZG4ub2sodGhpcywgYXJndW1lbnRzKSA6IG51bGwiIG9uZXJyb3I9IndpbmRvdy5fY2RuID8gX2Nkbi5mYWlsZWQodGhpcywgYXJndW1lbnRzKSA6IG51bGwiPjwvc2NyaXB0Pjxub3NjcmlwdD48bWV0YSBodHRwLWVxdWl2PSJyZWZyZXNoIiBjb250ZW50PSIwOyBVUkw9JnF1b3Q7XC8/cmVkaXI9JTJGZmlsZXMtcHJpJTJGVDJEUExFOEFZLUYwNTdUMTU4TDZCJTJGaW1nXzkwMzYuanBnJmFtcDtub2pzbW9kZT0xJnF1b3Q7Ij48L25vc2NyaXB0PjxzY3JpcHQgdHlwZT0idGV4dC9qYXZhc2NyaXB0Ij52YXIgc2FmZV9ob3N0cyA9IFsnYXBwLm9wdGltaXplbHkuY29tJywgJ3RpbnlzcGVjay5kZXYuc2xhY2suY29tJ107CgppZiAoc2VsZiAhPT0gdG9wICYmIHNhZmVfaG9zdHMuaW5kZXhPZih0b3AubG9jYXRpb24uaG9zdCkgPT09IC0xKSB7Cgl3aW5kb3cuZG9jdW1lbnQud3JpdGUoCgkJJ1x1MDAzQ3N0eWxlPmJvZHkgKiB7ZGlzcGxheTpub25lICFpbXBvcnRhbnQ7fVx1MDAzQy9zdHlsZT5cdTAwM0NhIGhyZWY9IiMiIG9uY2xpY2s9JyArCgkJCScidG9wLmxvY2F0aW9uLmhyZWY9d2luZG93LmxvY2F0aW9uLmhyZWYiIHN0eWxlPSJkaXNwbGF5OmJsb2NrICFpbXBvcnRhbnQ7cGFkZGluZzoxMHB4Ij5HbyB0byBTbGFjay5jb21cdTAwM0MvYT4nCgkpOwp9CgooZnVuY3Rpb24oKSB7Cgl2YXIgdGltZXI7CglpZiAoc2VsZiAhPT0gdG9wICYmIHNhZmVfaG9zdHMuaW5kZXhPZih0b3AubG9jYXRpb24uaG9zdCkgPT09IC0xKSB7CgkJdGltZXIgPSB3aW5kb3cuc2V0SW50ZXJ2YWwoZnVuY3Rpb24oKSB7CgkJCWlmICh3aW5kb3cpIHsKCQkJCXRyeSB7CgkJCQkJdmFyIHBhZ2VFbCA9IGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCdwYWdlJyk7CgkJCQkJdmFyIGNsaWVudEVsID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoJ2NsaWVudC11aScpOwoJCQkJCXZhciBzZWN0aW9uRWxzID0gZG9jdW1lbnQucXVlcnlTZWxlY3RvckFsbCgnbmF2LCBoZWFkZXIsIHNlY3Rpb24nKTsKCgkJCQkJcGFnZUVsLnBhcmVudE5vZGUucmVtb3ZlQ2hpbGQocGFnZUVsKTsKCQkJCQljbGllbnRFbC5wYXJlbnROb2RlLnJlbW92ZUNoaWxkKGNsaWVudEVsKTsKCQkJCQlmb3IgKHZhciBpID0gMDsgaSA8IHNlY3Rpb25FbHMubGVuZ3RoOyBpKyspIHsKCQkJCQkJc2VjdGlvbkVsc1tpXS5wYXJlbnROb2RlLnJlbW92ZUNoaWxkKHNlY3Rpb25FbHNbaV0pOwoJCQkJCX0KCQkJCQl3aW5kb3cuVFMgPSBudWxsOwoJCQkJCXdpbmRvdy5URCA9IG51bGw7CgkJCQkJd2luZG93LmNsZWFySW50ZXJ2YWwodGltZXIpOwoJCQkJfSBjYXRjaCAoZSkge30JCgkJCX0KCQl9LCAyMDApOwoJfQp9KSgpOzwvc2NyaXB0PjxzY3JpcHQgc3JjPSJodHRwczovL2Nkbi5jb29raWVsYXcub3JnL3NjcmlwdHRlbXBsYXRlcy9vdFNES1N0dWIuanMiIGRhdGEtZG9jdW1lbnQtbGFuZ3VhZ2U9InRydWUiIGRhdGEtZG9tYWluLXNjcmlwdD0iM2JjZDkwY2YtMWUzMi00NmQ3LWFkYmQtNjM0ZjY2YjY1YjdkIj53aW5kb3cuT25lVHJ1c3RMb2FkZWQgPSB0cnVlOzwvc2NyaXB0PjxzY3JpcHQ+d2luZG93Lk9uZVRydXN0TG9hZGVkID0gdHJ1ZTs8L3NjcmlwdD48c2NyaXB0PgoKZnVuY3Rpb24gYm9vdERyaWZ0KCkgewoJaWYgKHdpbmRvdy5kcmlmdF9sb2FkZWQpIHJldHVybjsKCWlmICghd2luZG93Lk9uZXRydXN0QWN0aXZlR3JvdXBzIHx8IGZhbHNlKSB7CgkJd2luZG93LmRyaWZ0X2xvYWRlZCA9IHRydWU7CgkJc2V0VGltZW91dCgKCQkJZnVuY3Rpb24oKSB7CgkJCXdpbmRvdy5nZW5lcmF0ZU5ld0NvbnRleHQgPSAoKSA9PiB7CgkJCQkJcmV0dXJuIHsKCQkJCQkJd2luZG93OiB7CgkJCQkJCQlsb2NhdGlvbjogewoJCQkJCQkJCWhhc2g6IHdpbmRvdy5sb2NhdGlvbi5oYXNoLAoJCQkJCQkJCWhvc3Q6IHdpbmRvdy5sb2NhdGlvbi5ob3N0LAoJCQkJCQkJCWhvc3RuYW1lOiB3aW5kb3cubG9jYXRpb24uaG9zdG5hbWUsCgkJCQkJCQkJaHJlZjogd2luZG93LmxvY2F0aW9uLmhyZWYsCgkJCQkJCQkJb3JpZ2luOiB3aW5kb3cubG9jYXRpb24ub3JpZ2luLAoJCQkJCQkJCXBhdGhuYW1lOiB3aW5kb3cubG9jYXRpb24ucGF0aG5hbWUsCgkJCQkJCQkJcG9ydDogd2luZG93LmxvY2F0aW9uLnBvcnQsCgkJCQkJCQkJcHJvdG9jb2w6IHdpbmRvdy5sb2NhdGlvbi5wcm90b2NvbCwKCQkJCQkJCQlzZWFyY2g6IHdpbmRvdy5sb2NhdGlvbi5zZWFyY2gsCgkJCQkJCQl9LAoJCQkJCQkJbmF2aWdhdG9yOiB7CgkJCQkJCQkJbGFuZ3VhZ2U6IHdpbmRvdy5uYXZpZ2F0b3IubGFuZ3VhZ2UsCgkJCQkJCQkJYnJvd3Nlckxhbmd1YWdlOiB3aW5kb3cubmF2aWdhdG9yLmJyb3dzZXJMYW5ndWFnZSwKCQkJCQkJCQl1c2VyQWdlbnQ6IHdpbmRvdy5uYXZpZ2F0b3IudXNlckFnZW50LAoJCQkJCQkJfSwKCQkJCQkJCWlubmVySGVpZ2h0OiB3aW5kb3cuaW5uZXJIZWlnaHQsCgkJCQkJCQlpbm5lcldpZHRoOiB3aW5kb3cuaW5uZXJXaWR0aCwKCQkJCQkJfSwKCQkJCQkJZG9jdW1lbnQ6IHsKCQkJCQkJCXRpdGxlOiBkb2N1bWVudC50aXRsZSwKCQkJCQkJCXJlZmVycmVyOiBkb2N1bWVudC5yZWZlcnJlciwKCQkJCQkJfSwKCQkJCQl9OwoJCQkJfTsKCQkJCXdpbmRvdy5hZGRFdmVudExpc3RlbmVyKCJyZXNpemUiLCAoKSA9PiB7CgkJCQkJY29uc3QgZHJpZnRpZnJhbWUgPSBkb2N1bWVudC5nZXRFbGVtZW50QnlJZCgiZHJpZnQtaWZyYW1lIik7CgkJCQkJaWYgKCFkcmlmdGlmcmFtZSkgcmV0dXJuOwoJCQkJCWRyaWZ0aWZyYW1lLmNvbnRlbnRXaW5kb3cucG9zdE1lc3NhZ2Uoe3R5cGU6ICJkcmlmdFVwZGF0ZUNvbnRleHQiLCBkYXRhOiBnZW5lcmF0ZU5ld0NvbnRleHQoKX0sICIqIik7CgkJCQl9KTsKCQkJCXdpbmRvdy5hZGRFdmVudExpc3RlbmVyKCJzY3JvbGwiLCAoZXZlbnQpID0+IHsKCQkJCQljb25zdCBkcmlmdGlmcmFtZSA9IGRvY3VtZW50LmdldEVsZW1lbnRCeUlkKCJkcmlmdC1pZnJhbWUiKTsKCQkJCQlpZiAoIWRyaWZ0aWZyYW1lKSByZXR1cm47CgkJCQkJZHJpZnRpZnJhbWUuY29udGVudFdpbmRvdy5wb3N0TWVzc2FnZSh7dHlwZTogImRyaWZ0UGFyZW50U2Nyb2xsIiwgZGF0YToge3Njcm9sbDogdHJ1ZX0sIHRhcmdldDogImRyaWZ0LnBhcmVudFNjcm9sbCJ9LCAiKiIpOwoJCQkJfSk7CgkJCQl3aW5kb3cuYWRkRXZlbnRMaXN0ZW5lcigibWVzc2FnZSIsIGZ1bmN0aW9uIChldmVudCkgewoJCQkJCWNvbnN0IGRyaWZ0aWZyYW1lID0gZG9jdW1lbnQuZ2V0RWxlbWVudEJ5SWQoImRyaWZ0LWlmcmFtZSIpOwoJCQkJCWlmICghZHJpZnRpZnJhbWUpIHJldHVybjsKCQkJCQlpZiAoIWRyaWZ0aWZyYW1lLmNvbnRlbnRXaW5kb3cgJiYgZXZlbnQuc291cmNlID09PSBkcmlmdGlmcmFtZS5jb250ZW50V2luZG93KSByZXR1cm47CgkJCQkJLy8gb24gc3RhcnR1cCAtIHBhc3MgY3JlYXRlZCBjb250ZXh0IGludG8gaWZyYW1lCgkJCQkJdmFyIG1lc3NhZ2UgPSBldmVudC5kYXRhOwoJCQkJCWlmIChtZXNzYWdlLnR5cGUgPT09ICJkcmlmdElmcmFtZVJlYWR5IikgewoJCQkJCQlkcmlmdGlmcmFtZS5jb250ZW50V2luZG93LnBvc3RNZXNzYWdlKHt0eXBlOiAiZHJpZnRTZXRDb250ZXh0IiwgZGF0YTogZ2VuZXJhdGVOZXdDb250ZXh0KCl9LCAiKiIpOwoJCQkJCX0KCQkJCQkvLyBvbiB3aWRnZXQgc2l6ZSBjaGFuZ2UgLSBhcHBseSBuZXcgc2l6ZSAvIHBvc2l0aW9uaW5nIHRvIGlmcmFtZQoJCQkJCWlmIChtZXNzYWdlLnR5cGUgPT09ICJkcmlmdElmcmFtZVJlc2l6ZSIpIHsKCQkJCQkJdmFyIHN0eWxlcyA9IG1lc3NhZ2UuZGF0YS5zdHlsZXM7CgkJCQkJCWZvciAodmFyIGtleSBpbiBzdHlsZXMpIHsKCQkJCQkJCWlmICghc3R5bGVzLmhhc093blByb3BlcnR5KGtleSkpIHsKCQkJCQkJCQljb250aW51ZTsKCQkJCQkJCX0KCQkJCQkJCWRyaWZ0aWZyYW1lLnN0eWxlLnNldFByb3BlcnR5KGtleSwgc3R5bGVzW2tleV0pOwoJCQkJCQl9CgkJCQkJfQoJCQkJfSk7CgkJCX0sCgkJMCk7Cgl9Cn0KZnVuY3Rpb24gT3B0YW5vbldyYXBwZXIoKSB7Cgl3aW5kb3cuZGF0YUxheWVyLnB1c2goeydldmVudCc6ICdPbmVUcnVzdFJlYWR5J30pOwoJaWYgKCFPcHRhbm9uLkdldERvbWFpbkRhdGEoKS5TaG93QWxlcnROb3RpY2UgfHwgZmFsc2UpIHsKCQlib290RHJpZnQoKTsKCQljb25zdCBib3R0b21CYW5uZXJFbCA9IGRvY3VtZW50LnF1ZXJ5U2VsZWN0b3IoJy5jLWFubm91bmNlbWVudC1iYW5uZXItYm90dG9tJyk7CgkJaWYgKGJvdHRvbUJhbm5lckVsICE9PSBudWxsKSB7CgkJCWJvdHRvbUJhbm5lckVsLmNsYXNzTGlzdC5yZW1vdmUoJ2MtYW5ub3VuY2VtZW50LWJhbm5lci1ib3R0b20taW52aXNpYmxlJyk7CgkJfQoKCX0KCU9wdGFub24uT25Db25zZW50Q2hhbmdlZChmdW5jdGlvbigpIHsKCQlib290RHJpZnQoKTsKCQljb25zdCBib3R0b21CYW5uZXJFbCA9IGRvY3VtZW50LnF1ZXJ5U2VsZWN0b3IoJy5jLWFubm91bmNlbWVudC1iYW5uZXItYm90dG9tJyk7CgkJaWYgKGJvdHRvbUJhbm5lckVsICE9PSBudWxsKSB7CgkJCWJvdHRvbUJhbm5lckVsLmNsYXNzTGlzdC5yZW1vdmUoJ2MtYW5ub3VuY2VtZW50LWJhbm5lci1ib3R0b20taW52aXNpYmxlJyk7CgkJfQoJfSk7Cn08L3NjcmlwdD48bWV0YSBuYW1lPSJmYWNlYm9vay1kb21haW4tdmVyaWZpY2F0aW9uIiBjb250ZW50PSJjaGl3c2FqcG95Ym4yY25xeWo5dzhtdnJleTU2bTAiPjxzY3JpcHQgdHlwZT0idGV4dC9qYXZhc2NyaXB0Ij4KZG9jdW1lbnQuYWRkRXZlbnRMaXN0ZW5lcigiRE9NQ29udGVudExvYWRlZCIsIGZ1bmN0aW9uKGUpIHsKCXZhciBndG1EYXRhTGF5ZXIgPSB3aW5kb3cuZGF0YUxheWVyIHx8IFtdOwoJdmFyIGd0bVRhZ3MgPSBkb2N1bWVudC5xdWVyeVNlbGVjdG9yQWxsKCcqW2RhdGEtZ3RtLWNsaWNrXScpOwoJdmFyIGd0bUNsaWNrSGFuZGxlciA9IGZ1bmN0aW9uKGMpIHsKCQl2YXIgZ3RtX2V2ZW50cyA9IHRoaXMuZ2V0QXR0cmlidXRlKCdkYXRhLWd0bS1jbGljaycpOwoJCWlmICghZ3RtX2V2ZW50cykgcmV0dXJuOwoJCXZhciBndG1fZXZlbnRzX2FyciA9IGd0bV9ldmVudHMuc3BsaXQoIiwiKTsKCQlmb3IodmFyIGU9MDsgZSA8IGd0bV9ldmVudHNfYXJyLmxlbmd0aDsgZSsrKSB7CgkJCXZhciBldiA9IGd0bV9ldmVudHNfYXJyW2VdLnRyaW0oKTsKCQkJZ3RtRGF0YUxheWVyLnB1c2goeyAnZXZlbnQnOiBldiB9KTsKCQl9Cgl9OwoJZm9yKHZhciBnPTA7IGcgPCBndG1UYWdzLmxlbmd0aDsgZysrKXsKCQl2YXIgZWxlbSA9IGd0bVRhZ3NbZ107CgkJZWxlbS5hZGRFdmVudExpc3RlbmVyKCdjbGljaycsIGd0bUNsaWNrSGFuZGxlcik7Cgl9Cn0pOwo8L3NjcmlwdD48c2NyaXB0IHR5cGU9InRleHQvamF2YXNjcmlwdCI+CihmdW5jdGlvbihlLGMsYixmLGQsZyxhKXtlLlNsYWNrQmVhY29uT2JqZWN0PWQ7CmVbZF09ZVtkXXx8ZnVuY3Rpb24oKXsoZVtkXS5xPWVbZF0ucXx8W10pLnB1c2goWzEqbmV3IERhdGUoKSxhcmd1bWVudHNdKX07CmVbZF0ubD0xKm5ldyBEYXRlKCk7Zz1jLmNyZWF0ZUVsZW1lbnQoYik7YT1jLmdldEVsZW1lbnRzQnlUYWdOYW1lKGIpWzBdOwpnLmFzeW5jPTE7Zy5zcmM9ZjthLnBhcmVudE5vZGUuaW5zZXJ0QmVmb3JlKGcsYSkKfSkod2luZG93LGRvY3VtZW50LCJzY3JpcHQiLCJodHRwczovL2Euc2xhY2stZWRnZS5jb20vYnYxLTEwL3NsYWNrX2JlYWNvbi5hOWQ0Zjc4YTQzYWJkNmQ5NDk1ZC5taW4uanMiLCJzYiIpOwp3aW5kb3cuc2IoJ3NldCcsICd0b2tlbicsICczMzA3ZjQzNjk2M2UwMmQ0ZjllYjg1Y2U1MTU5NzQ0YycpOwp3aW5kb3cuc2IoJ3RyYWNrJywgJ3BhZ2V2aWV3Jyk7Cjwvc2NyaXB0PjxzY3JpcHQgdHlwZT0idGV4dC9qYXZhc2NyaXB0Ij52YXIgVFNfbGFzdF9sb2dfZGF0ZSA9IG51bGw7CnZhciBUU01ha2VMb2dEYXRlID0gZnVuY3Rpb24oKSB7Cgl2YXIgZGF0ZSA9IG5ldyBEYXRlKCk7CgoJdmFyIHkgPSBkYXRlLmdldEZ1bGxZZWFyKCk7Cgl2YXIgbW8gPSBkYXRlLmdldE1vbnRoKCkrMTsKCXZhciBkID0gZGF0ZS5nZXREYXRlKCk7CgoJdmFyIHRpbWUgPSB7CgkgIGg6IGRhdGUuZ2V0SG91cnMoKSwKCSAgbWk6IGRhdGUuZ2V0TWludXRlcygpLAoJICBzOiBkYXRlLmdldFNlY29uZHMoKSwKCSAgbXM6IGRhdGUuZ2V0TWlsbGlzZWNvbmRzKCkKCX07CgoJT2JqZWN0LmtleXModGltZSkubWFwKGZ1bmN0aW9uKG1vbWVudCwgaW5kZXgpIHsKCQlpZiAobW9tZW50ID09ICdtcycpIHsKCQkJaWYgKHRpbWVbbW9tZW50XSA8IDEwKSB7CgkJCQl0aW1lW21vbWVudF0gPSB0aW1lW21vbWVudF0rJzAwJzsKCQkJfSBlbHNlIGlmICh0aW1lW21vbWVudF0gPCAxMDApIHsKCQkJCXRpbWVbbW9tZW50XSA9IHRpbWVbbW9tZW50XSsnMCc7CgkJCX0KCQl9IGVsc2UgaWYgKHRpbWVbbW9tZW50XSA8IDEwKSB7CgkJCXRpbWVbbW9tZW50XSA9ICcwJyArIHRpbWVbbW9tZW50XTsKCQl9Cgl9KTsKCgl2YXIgc3RyID0geSArICcvJyArIG1vICsgJy8nICsgZCArICcgJyArIHRpbWUuaCArICc6JyArIHRpbWUubWkgKyAnOicgKyB0aW1lLnMgKyAnLicgKyB0aW1lLm1zOwoJaWYgKFRTX2xhc3RfbG9nX2RhdGUpIHsKCQl2YXIgZGlmZiA9IGRhdGUtVFNfbGFzdF9sb2dfZGF0ZTsKCQkvL3N0cis9ICcgKCcrZGlmZisnbXMpJzsKCX0KCVRTX2xhc3RfbG9nX2RhdGUgPSBkYXRlOwoJcmV0dXJuIHN0cisnICc7Cn0KCnZhciBwYXJzZURlZXBMaW5rUmVxdWVzdCA9IGZ1bmN0aW9uKGNvZGUpIHsKCXZhciBtID0gY29kZS5tYXRjaCgvImlkIjoiKFtDREddW0EtWjAtOV17OCx9KSIvKTsKCXZhciBpZCA9IG0gPyBtWzFdIDogbnVsbDsKCgltID0gY29kZS5tYXRjaCgvInRlYW0iOiIoVFtBLVowLTldezgsfSkiLyk7Cgl2YXIgdGVhbSA9IG0gPyBtWzFdIDogbnVsbDsKCgltID0gY29kZS5tYXRjaCgvIm1lc3NhZ2UiOiIoWzAtOV0rXC5bMC05XSspIi8pOwoJdmFyIG1lc3NhZ2UgPSBtID8gbVsxXSA6IG51bGw7CgoJcmV0dXJuIHsgaWQ6IGlkLCB0ZWFtOiB0ZWFtLCBtZXNzYWdlOiBtZXNzYWdlIH07Cn0KCmlmICgncmVuZGVyZXJFdmFsQXN5bmMnIGluIHdpbmRvdykgewoJdmFyIG9yaWdSZW5kZXJlckV2YWxBc3luYyA9IHdpbmRvdy5yZW5kZXJlckV2YWxBc3luYzsKCXdpbmRvdy5yZW5kZXJlckV2YWxBc3luYyA9IGZ1bmN0aW9uKGJsb2IpIHsKCQl0cnkgewoJCQl2YXIgZGF0YSA9IEpTT04ucGFyc2UoZGVjb2RlVVJJQ29tcG9uZW50KGF0b2IoYmxvYikpKTsKCQkJaWYgKGRhdGEuY29kZS5tYXRjaCgvaGFuZGxlRGVlcExpbmsvKSkgewoJCQkJdmFyIHJlcXVlc3QgPSBwYXJzZURlZXBMaW5rUmVxdWVzdChkYXRhLmNvZGUpOwoJCQkJaWYgKCFyZXF1ZXN0LmlkIHx8ICFyZXF1ZXN0LnRlYW0gfHwgIXJlcXVlc3QubWVzc2FnZSkgcmV0dXJuOwoKCQkJCXJlcXVlc3QuY21kID0gJ2NoYW5uZWwnOwoJCQkJVFNTU0IuaGFuZGxlRGVlcExpbmtXaXRoQXJncyhKU09OLnN0cmluZ2lmeShyZXF1ZXN0KSk7CgkJCQlyZXR1cm47CgkJCX0gZWxzZSB7CgkJCQlvcmlnUmVuZGVyZXJFdmFsQXN5bmMoYmxvYik7CgkJCX0KCQl9IGNhdGNoIChlKSB7CgkJfQoJfQp9PC9zY3JpcHQ+PHNjcmlwdCB0eXBlPSJ0ZXh0L2phdmFzY3JpcHQiPnZhciBUU1NTQiA9IHsKCWNhbGw6IGZ1bmN0aW9uKCkgewoJCXJldHVybiBmYWxzZTsKCX0KfTs8L3NjcmlwdD48dGl0bGU+U2xhY2s8L3RpdGxlPjxtZXRhIG5hbWU9InJlZmVycmVyIiBjb250ZW50PSJuby1yZWZlcnJlciI+PG1ldGEgbmFtZT0ic3VwZXJmaXNoIiBjb250ZW50PSJub2Zpc2giPjxtZXRhIG5hbWU9ImF1dGhvciIgY29udGVudD0iU2xhY2siPjxtZXRhIG5hbWU9ImRlc2NyaXB0aW9uIiBjb250ZW50PSIiPjxtZXRhIG5hbWU9ImtleXdvcmRzIiBjb250ZW50PSIiPjwvaGVhZD48Ym9keSBjbGFzcz0iZnVsbF9oZWlnaHQiPjxkaXYgaWQ9InBhZ2VfY29udGVudHMiPjxkaXYgaWQ9InByb3BzX25vZGUiIGRhdGEtcHJvcHM9InsmcXVvdDtsb2dnZWRJblRlYW1zJnF1b3Q7OltdLCZxdW90O2VudHJ5UG9pbnQmcXVvdDs6JnF1b3Q7JnF1b3Q7LCZxdW90O2lzUGFpZFRlYW0mcXVvdDs6ZmFsc2UsJnF1b3Q7dGVhbU5hbWUmcXVvdDs6JnF1b3Q7QUtVUkVZJnF1b3Q7LCZxdW90O3RlYW1Eb21haW4mcXVvdDs6JnF1b3Q7YWt1cmV5JnF1b3Q7LCZxdW90O2VuY29kZWRUZWFtSWQmcXVvdDs6JnF1b3Q7VDJEUExFOEFZJnF1b3Q7LCZxdW90O2VtYWlsSnVzdFNlbnQmcXVvdDs6ZmFsc2UsJnF1b3Q7c2hvdWxkUmVkaXJlY3QmcXVvdDs6dHJ1ZSwmcXVvdDtyZWRpcmVjdFVSTCZxdW90OzomcXVvdDtcL2ZpbGVzLXByaVwvVDJEUExFOEFZLUYwNTdUMTU4TDZCXC9pbWdfOTAzNi5qcGcmcXVvdDssJnF1b3Q7cmVkaXJlY3RRcyZxdW90OzomcXVvdDtcLz9yZWRpcj0lMkZmaWxlcy1wcmklMkZUMkRQTEU4QVktRjA1N1QxNThMNkIlMkZpbWdfOTAzNi5qcGcmcXVvdDssJnF1b3Q7cmVtZW1iZXImcXVvdDs6ZmFsc2UsJnF1b3Q7aGFzUmVtZW1iZXImcXVvdDs6dHJ1ZSwmcXVvdDtub1NTTyZxdW90OzpmYWxzZSwmcXVvdDtjcnVtYlZhbHVlJnF1b3Q7OiZxdW90O3MtMTY4NDQzMDE2OC0zNGUzNjYwMDcxMDQxMTM0ZTlhMmI3MmZhMTUxZmRmNWYzNjU4NGI5YjI4ZGY5Y2Y4NDVhZGM3YzY2MGEyOWRlLVx1MjYwMyZxdW90OywmcXVvdDtpc1NTQiZxdW90OzpmYWxzZSwmcXVvdDtpc1NTQlNpZ25JbiZxdW90OzpmYWxzZSwmcXVvdDtpc1NTQlNvbmljU2lnbkluJnF1b3Q7OmZhbHNlLCZxdW90O1NTQlZlcnNpb24mcXVvdDs6JnF1b3Q7JnF1b3Q7LCZxdW90O2hhc0VtYWlsRXJyb3ImcXVvdDs6ZmFsc2UsJnF1b3Q7ZW1haWxWYWx1ZSZxdW90OzomcXVvdDsmcXVvdDssJnF1b3Q7aGFzUGFzc3dvcmRFcnJvciZxdW90OzpmYWxzZSwmcXVvdDtpc01vYmlsZUJyb3dzZXImcXVvdDs6ZmFsc2UsJnF1b3Q7aGFzQXV0aFJlbG9naW5GbG93JnF1b3Q7OmZhbHNlLCZxdW90O2hhc1JhdGVMaW1pdCZxdW90OzpmYWxzZSwmcXVvdDtyZWNhcHRjaGFTaXRla2V5JnF1b3Q7OiZxdW90OzZMY1FRaVlVQUFBQUFEeEpIcmloQUNxRDV3ZjNsa3NtOWpiblJZNWsmcXVvdDssJnF1b3Q7aGFzU21zUmF0ZUxpbWl0JnF1b3Q7OmZhbHNlLCZxdW90O2ZvcmdvdFBhc3N3b3JkTGluayZxdW90OzomcXVvdDtcL2ZvcmdvdCZxdW90OywmcXVvdDtzaG93U2lnbnVwRW1haWxMaW5rJnF1b3Q7OnRydWUsJnF1b3Q7Z2V0U3RhcnRlZExpbmsmcXVvdDs6JnF1b3Q7aHR0cHM6XC9cL3NsYWNrLmNvbVwvZ2V0LXN0YXJ0ZWQjXC9maW5kJnF1b3Q7LCZxdW90O2xvZ2dlZE91dFBhc3N3b3JkUmVzZXRTZW50QWRkcmVzcyZxdW90OzomcXVvdDsmcXVvdDssJnF1b3Q7aXNTU09BdXRoTW9kZSZxdW90OzpmYWxzZSwmcXVvdDtpc05vcm1hbEF1dGhNb2RlJnF1b3Q7OnRydWUsJnF1b3Q7c2lnbmluVXJsJnF1b3Q7OiZxdW90O2h0dHBzOlwvXC9zbGFjay5jb21cL3NpZ25pbiZxdW90OywmcXVvdDtzaWduaW5GaW5kVXJsJnF1b3Q7OiZxdW90O2h0dHBzOlwvXC9zbGFjay5jb21cL3NpZ25pblwvZmluZCZxdW90OywmcXVvdDtzc2JSZWxvZ2luJnF1b3Q7OiZxdW90OyZxdW90OywmcXVvdDtpc0xvZ2dlZE91dDJmYSZxdW90OzpmYWxzZSwmcXVvdDtpc0xvZ2dlZE91dFRlYW0yZmEmcXVvdDs6ZmFsc2UsJnF1b3Q7aXNMb2dnZWRPdXRTZWxmUGFzc3dvcmRSZXNldCZxdW90OzpmYWxzZSwmcXVvdDtpc0xvZ2dlZE91dFBhc3N3b3JkUmVzZXQmcXVvdDs6ZmFsc2UsJnF1b3Q7aXNMb2dnZWRPdXRHb2RQYXNzd29yZFJlc2V0JnF1b3Q7OmZhbHNlLCZxdW90O2lzTG9nZ2VkT3V0T3duZXJQYXNzd29yZFJlc2V0JnF1b3Q7OmZhbHNlLCZxdW90O2lzTG9nZ2VkT3V0T3duZXJTU09SZXNldCZxdW90OzpmYWxzZSwmcXVvdDtpc0xvZ2dlZE91dFNTT01heWJlUmVxdWlyZWQmcXVvdDs6ZmFsc2UsJnF1b3Q7aXNMb2dnZWRPdXRSZWRpcmVjdCZxdW90Ozp0cnVlLCZxdW90O3RlYW1BdXRoTW9kZSZxdW90OzpudWxsLCZxdW90O2F1dGhNb2RlR29vZ2xlJnF1b3Q7OiZxdW90O2dvb2dsZSZxdW90OywmcXVvdDtzYW1sUHJvdmlkZXJMYWJlbCZxdW90OzpudWxsLCZxdW90O2Vycm9yU291cmNlJnF1b3Q7OiZxdW90OyZxdW90OywmcXVvdDtlcnJvck1pc3NpbmcmcXVvdDs6ZmFsc2UsJnF1b3Q7ZXJyb3JOb1VzZXImcXVvdDs6ZmFsc2UsJnF1b3Q7ZXJyb3JEZWxldGVkJnF1b3Q7OmZhbHNlLCZxdW90O2Vycm9yUGFzc3dvcmQmcXVvdDs6ZmFsc2UsJnF1b3Q7ZXJyb3JTU09Ob093bmVyJnF1b3Q7OmZhbHNlLCZxdW90O2Vycm9yU1NPTm9uUkEmcXVvdDs6ZmFsc2UsJnF1b3Q7ZXJyb3JUd29GYWN0b3JXcm9uZyZxdW90OzpmYWxzZSwmcXVvdDtlcnJvclNtc1JhdGVMaW1pdCZxdW90OzpmYWxzZSwmcXVvdDtlcnJvckNvbmZpcm1lZCZxdW90OzpmYWxzZSwmcXVvdDtlcnJvck5vUGFzc3dvcmQmcXVvdDs6ZmFsc2UsJnF1b3Q7ZXJyb3JUd29GYWN0b3JTdGF0ZSZxdW90OzpmYWxzZSwmcXVvdDtoYXNFbWFpbE9uRG9tYWluJnF1b3Q7OnRydWUsJnF1b3Q7dHJ1bmNhdGVkRW1haWxEb21haW5zJnF1b3Q7Om51bGwsJnF1b3Q7dHJ1bmNhdGVkRW1haWxEb21haW5zQ291bnQmcXVvdDs6MCwmcXVvdDtmb3JtYXR0ZWRFbWFpbERvbWFpbnMmcXVvdDs6JnF1b3Q7QGFrdXJleS5jb20mcXVvdDssJnF1b3Q7aXNSZWxvZ2luRmxvdyZxdW90OzpmYWxzZSwmcXVvdDtkb3dubG9hZExpbmtTaWduaW5DVEEmcXVvdDs6eyZxdW90O2xpbmtVcmwmcXVvdDs6JnF1b3Q7XC9nZXQtc3RhcnRlZCNcL2NyZWF0ZSZxdW90OywmcXVvdDtpc0Rvd25sb2FkJnF1b3Q7OmZhbHNlfSwmcXVvdDt0d29GYWN0b3JSZXF1aXJlZCZxdW90OzpmYWxzZSwmcXVvdDt1c2luZ0JhY2t1cCZxdW90OzpudWxsLCZxdW90O3R3b0ZhY3RvclR5cGUmcXVvdDs6bnVsbCwmcXVvdDt0d29GYWN0b3JCYWNrdXBUeXBlJnF1b3Q7Om51bGwsJnF1b3Q7dHdvRmFjdG9yUmVxdWlyZWRNTCZxdW90OzpudWxsLCZxdW90O2F1dGhjb2RlSW5wdXRUeXBlJnF1b3Q7OiZxdW90O3RleHQmcXVvdDssJnF1b3Q7YmFja3VwUGhvbmVOdW1iZXImcXVvdDs6bnVsbCwmcXVvdDtmb3Jnb3RQYXNzd29yZEVycm9yJnF1b3Q7OiZxdW90OyZxdW90OywmcXVvdDtyZXNldExpbmtTZW50JnF1b3Q7OmZhbHNlLCZxdW90O3VzZXJPYXV0aCZxdW90Ozp7JnF1b3Q7YXBwbGUmcXVvdDs6eyZxdW90O2VuYWJsZWQmcXVvdDs6dHJ1ZSwmcXVvdDtyZWRpcmVjdF91cmwmcXVvdDs6JnF1b3Q7aHR0cHM6XC9cL2FrdXJleS5zbGFjay5jb21cL3dvcmtzcGFjZS1zaWduaW5cL29hdXRoXC9hcHBsZVwvc3RhcnQ/cmVkaXI9JTJGZmlsZXMtcHJpJTJGVDJEUExFOEFZLUYwNTdUMTU4TDZCJTJGaW1nXzkwMzYuanBnJmFtcDtpc19zc2JfYnJvd3Nlcl9zaWduaW49JnF1b3Q7fSwmcXVvdDtnb29nbGUmcXVvdDs6eyZxdW90O2VuYWJsZWQmcXVvdDs6dHJ1ZSwmcXVvdDtyZWRpcmVjdF91cmwmcXVvdDs6JnF1b3Q7aHR0cHM6XC9cL2FrdXJleS5zbGFjay5jb21cL3dvcmtzcGFjZS1zaWduaW5cL29hdXRoXC9nb29nbGVcL3N0YXJ0P3JlZGlyPSUyRmZpbGVzLXByaSUyRlQyRFBMRThBWS1GMDU3VDE1OEw2QiUyRmltZ185MDM2LmpwZyZhbXA7aXNfc3NiX2Jyb3dzZXJfc2lnbmluPSZxdW90O319LCZxdW90O2lzVXJnZW50QmFubmVyRXhwT24mcXVvdDs6ZmFsc2UsJnF1b3Q7aXNXYXJuaW5nQmFubmVyRXhwT24mcXVvdDs6dHJ1ZSwmcXVvdDtzaWduSW5XaXRoUGFzc3dvcmQmcXVvdDs6ZmFsc2V9Ij48L2Rpdj48L2Rpdj48c2NyaXB0IHR5cGU9InRleHQvamF2YXNjcmlwdCI+Ci8qKgogKiBBIHBsYWNlaG9sZGVyIGZ1bmN0aW9uIHRoYXQgdGhlIGJ1aWxkIHNjcmlwdCB1c2VzIHRvCiAqIHJlcGxhY2UgZmlsZSBwYXRocyB3aXRoIHRoZWlyIENETiB2ZXJzaW9ucy4KICoKICogQHBhcmFtIHtTdHJpbmd9IGZpbGVfcGF0aCAtIEZpbGUgcGF0aAogKiBAcmV0dXJucyB7U3RyaW5nfQogKi8KZnVuY3Rpb24gdnZ2KGZpbGVfcGF0aCkgewoJCSB2YXIgdnZ2X3dhcm5pbmcgPSAnWW91IGNhbm5vdCB1c2UgdnZ2IG9uIGR5bmFtaWMgdmFsdWVzLiBQbGVhc2UgbWFrZSBzdXJlIHlvdSBvbmx5IHBhc3MgaW4gc3RhdGljIGZpbGUgcGF0aHMuJzsgaWYgKHdpbmRvdy5UUyAmJiB3aW5kb3cuVFMud2FybikgeyB3aW5kb3cuVFMud2Fybih2dnZfd2FybmluZyk7IH0gZWxzZSB7IGNvbnNvbGUud2Fybih2dnZfd2FybmluZyk7IH0gCglyZXR1cm4gZmlsZV9wYXRoOwp9Cgp2YXIgY2RuX3VybCA9ICJodHRwczpcL1wvYS5zbGFjay1lZGdlLmNvbSI7CnZhciB2dnZfYWJzX3VybCA9ICJodHRwczpcL1wvc2xhY2suY29tXC8iOwp2YXIgaW5jX2pzX3NldHVwX2RhdGEgPSB7CgllbW9qaV9zaGVldHM6IHsKCQlhcHBsZTogJ2h0dHBzOi8vYS5zbGFjay1lZGdlLmNvbS84MDU4OC9pbWcvZW1vamlfMjAxN18xMl8wNi9zaGVldF9hcHBsZV82NF9pbmRleGVkXzI1Ni5wbmcnLAoJCWdvb2dsZTogJ2h0dHBzOi8vYS5zbGFjay1lZGdlLmNvbS84MDU4OC9pbWcvZW1vamlfMjAxN18xMl8wNi9zaGVldF9nb29nbGVfNjRfaW5kZXhlZF8yNTYucG5nJywKCX0sCn07Cjwvc2NyaXB0PjxzY3JpcHQgbm9uY2U9IiIgdHlwZT0idGV4dC9qYXZhc2NyaXB0Ij4JLy8gY29tbW9uIGJvb3RfZGF0YQoJdmFyIGJvb3RfZGF0YSA9IHsiY2RuIjp7ImVkZ2VzIjpbImh0dHBzOlwvXC9hLnNsYWNrLWVkZ2UuY29tXC8iLCJodHRwczpcL1wvYi5zbGFjay1lZGdlLmNvbVwvIiwiaHR0cHM6XC9cL2Euc2xhY2stZWRnZS5jb21cLyJdLCJhdmF0YXJzIjoiaHR0cHM6XC9cL2NhLnNsYWNrLWVkZ2UuY29tXC8iLCJkb3dubG9hZHMiOiJodHRwczpcL1wvZG93bmxvYWRzLnNsYWNrLWVkZ2UuY29tXC8iLCJmaWxlcyI6Imh0dHBzOlwvXC9zbGFjay1maWxlcy5jb21cLyJ9LCJmZWF0dXJlX2J1aWxkZXJfc3Rvcnlfc3RlcCI6ZmFsc2UsImZlYXR1cmVfZGF5Ml9zaGFyZV9tb2RhbCI6dHJ1ZSwiZmVhdHVyZV90aW55c3BlY2siOmZhbHNlLCJmZWF0dXJlX29sdWdfZXNjX2NoYW5uZWxzX3dvcmsiOnRydWUsImZlYXR1cmVfb2x1Z19yZW1vdmVfcmVxdWlyZWRfd29ya3NwYWNlX3NldHRpbmciOmZhbHNlLCJmZWF0dXJlX2RhdGFfdGFibGVfaW5fb3JnX2xldmVsX3VzZXJfZ3JvdXBzIjpmYWxzZSwiZmVhdHVyZV9vcmdfc2V0dGluZ3NfbTExbiI6ZmFsc2UsImZlYXR1cmVfZGVwcmVjYXRlX2dldF9tZW1iZXJfYnlfbmFtZSI6ZmFsc2UsImZlYXR1cmVfYWRkX21lc3NhZ2VfcGVyZiI6ZmFsc2UsImZlYXR1cmVfYW1hem9uX2ExMXlfY3VzdG9tX3N0YXR1c19lbW9qaSI6dHJ1ZSwiZmVhdHVyZV9maWxlX3RocmVhZHMiOnRydWUsImZlYXR1cmVfYnJvYWRjYXN0X2luZGljYXRvciI6dHJ1ZSwiZmVhdHVyZV9uZXdfcmVwbGllc19hZnRlcl9iY2FzdCI6dHJ1ZSwiZmVhdHVyZV9zb25pY19lbW9qaSI6dHJ1ZSwiZmVhdHVyZV9hdHRhY2htZW50c19pbmxpbmUiOmZhbHNlLCJmZWF0dXJlX2Rlc2t0b3Bfc3ltcHRvbV9ldmVudHMiOnRydWUsImZlYXR1cmVfZW50X2FkbWluX2FwcHJvdmVkX2FwcHNfdjIiOnRydWUsImZlYXR1cmVfc2hhcmVkX2NoYW5uZWxzX211bHRpX29yZ19xYV9saW1pdF9vdmVycmlkZSI6ZmFsc2UsImZlYXR1cmVfZ2Rwcl91c2VyX2pvaW5fdG9zIjp0cnVlLCJmZWF0dXJlX3VzZXJfaW52aXRlX3Rvc19hcHJpbF8yMDE4Ijp0cnVlLCJmZWF0dXJlX2VucmljaF9mZXRjaF90ZWFtX3VzZXJfZnJvbV9kYiI6dHJ1ZSwiZmVhdHVyZV9jaGFubmVsX21nbXRfbWVzc2FnZV9jb3VudCI6ZmFsc2UsImZlYXR1cmVfd2hpdGVsaXN0X3plbmRlc2tfY2hhdF93aWRnZXQiOmZhbHNlLCJmZWF0dXJlX3VzZV9pbWdwcm94eV9yZXNpemluZyI6dHJ1ZSwiZmVhdHVyZV9ib2FyZHNfaW5fZGV2IjpmYWxzZSwiZmVhdHVyZV9kaXNhYmxlX2JrX2luX3RocmVhZCI6dHJ1ZSwiZmVhdHVyZV9jaGFubmVsX2V4cG9ydHMiOmZhbHNlLCJmZWF0dXJlX2RvY3NfbWVudGlvbnNfYW5kX2NoYW5uZWxzIjpmYWxzZSwiZmVhdHVyZV9jYWxsc19zdXJ2ZXlfcmVxdWVzdF9yZXNwb25zZSI6dHJ1ZSwiZmVhdHVyZV9zaWRlYmFyX3RoZW1lX3VuZG8iOnRydWUsImZlYXR1cmVfYWxsb3dfaW50cmFfd29yZF9mb3JtYXR0aW5nIjp0cnVlLCJmZWF0dXJlX3NsaW1fc2Nyb2xsYmFyIjpmYWxzZSwiZmVhdHVyZV9lZGdlX3VwbG9hZF9wcm94eV9jaGVjayI6dHJ1ZSwiZmVhdHVyZV91bnJlYWRfY291bnRzX2RlbGF5Ijp0cnVlLCJmZWF0dXJlX2xlZ2FjeV9maWxlX3VwbG9hZF9hbmFseXRpY3MiOnRydWUsImZlYXR1cmVfbXBkbV9saW1pdF9jaGFubmVsX2NyZWF0aW9uIjpmYWxzZSwiZmVhdHVyZV9zbmlwcGV0X21vZGVzX2kxOG4iOmZhbHNlLCJmZWF0dXJlX21zX2xhdGVzdCI6dHJ1ZSwiZmVhdHVyZV9yb29tc19qb2luX3VybCI6ZmFsc2UsImZlYXR1cmVfY3VzdG9tX3N0YXR1c19jYWxlbmRhcl9zeW5jX2NvcHkiOnRydWUsImZlYXR1cmVfY3VzdG9tX3N0YXR1c19jYWxlbmRhcl9zeW5jIjp0cnVlLCJmZWF0dXJlX21hc2tfdW5kb2N1bWVudGVkX2Vycm9ycyI6ZmFsc2UsImZlYXR1cmVfYXBwX3ZpZXdzX3JlbWluZGVycyI6dHJ1ZSwiZmVhdHVyZV9yZW1pbmRlcnNfb3JnX3NoYXJkIjpmYWxzZSwiZmVhdHVyZV9yZW1pbmRlcnNfZ3JpZF9taWdyYXRpb25zX29yZ19zaGFyZCI6ZmFsc2UsImZlYXR1cmVfYmxvY2tzX3JlbWluZGVyc19saXN0IjpmYWxzZSwiZmVhdHVyZV9tZXNzYWdlX2Jsb2NrcyI6ZmFsc2UsImZlYXR1cmVfc2V0X3R6X2F1dG9tYXRpY2FsbHkiOnRydWUsImZlYXR1cmVfY29uZmlybV9jbGVhcl9hbGxfdW5yZWFkc19wcmVmIjp0cnVlLCJmZWF0dXJlX2Jsb2NrX21vdW50cyI6dHJ1ZSwiZmVhdHVyZV9hdHRhY2htZW50c192MiI6dHJ1ZSwiZmVhdHVyZV9ncm91cF9ibG9jayI6ZmFsc2UsImZlYXR1cmVfc2hvd19ibG9ja19raXRfaW5fc2hhcmVfZGlhbG9ncyI6ZmFsc2UsImZlYXR1cmVfYmxvY2tfa2l0X3JhbmdlX2RhdGVwaWNrZXIiOmZhbHNlLCJmZWF0dXJlX2RlbGV0ZV9hcHBfaG9tZXNfYXNzb2NpYXRlZF93aXRoX2RlbGV0ZWRfc2VydmljZSI6dHJ1ZSwiZmVhdHVyZV9zb2Z0X2RlbGV0ZV9hcHBfaG9tZXNfb25fdXNlcl9kZWFjdGl2YXRpb24iOmZhbHNlLCJmZWF0dXJlX2JlYWNvbl9qc19lcnJvcnMiOmZhbHNlLCJmZWF0dXJlX3VzZXJfYXBwX2Rpc2FibGVfc3BlZWRfYnVtcCI6dHJ1ZSwiZmVhdHVyZV9hcHBzX21hbmFnZV9wZXJtaXNzaW9uc19zY29wZV9jaGFuZ2VzIjp0cnVlLCJmZWF0dXJlX3JlbWluZGVyX2Nyb3NzX3dvcmtzcGFjZSI6dHJ1ZSwiZmVhdHVyZV9wMnAiOmZhbHNlLCJmZWF0dXJlX3BhZ2VzX2V4YW1wbGUiOmZhbHNlLCJmZWF0dXJlX2lhcDEiOmZhbHNlLCJmZWF0dXJlX2lhX2dhIjp0cnVlLCJmZWF0dXJlX2lhX2kxOG4iOnRydWUsImZlYXR1cmVfaWFfbWVtYmVyX3Byb2ZpbGUiOnRydWUsImZlYXR1cmVfd29ya3NwYWNlX3NjaW1fbWFuYWdlbWVudCI6ZmFsc2UsImZlYXR1cmVfZGVza3RvcF9yZWxvYWRfb25fZ2VuZXJpY19lcnJvciI6dHJ1ZSwiZmVhdHVyZV9kZXNrdG9wX2V4dGVuZF9hcHBfbWVudSI6dHJ1ZSwiZmVhdHVyZV9kZXNrdG9wX3Jlc3RhcnRfc2VydmljZV93b3JrZXIiOmZhbHNlLCJmZWF0dXJlX2Rlc2t0b3Bfc3lzdGVtX25vdGlmaWNhdGlvbl9wbGF5YmFjayI6ZmFsc2UsImZlYXR1cmVfYm90c19ub3RfbWVtYmVycyI6dHJ1ZSwiZmVhdHVyZV93dGFfc3RvcF9jcmVhdGlvbiI6dHJ1ZSwiZmVhdHVyZV9wbGF0Zm9ybV9kZXByZWNhdGlvbnNfZmUiOnRydWUsImZlYXR1cmVfbm9fc29ja2V0X21vZGUiOmZhbHNlLCJmZWF0dXJlX25vX2NhbGxiYWNrX2lkX2VkaXQiOmZhbHNlLCJmZWF0dXJlX2FkbWluX2VtYWlsX2NoYW5nZV9jb25maXJtIjpmYWxzZSwiZmVhdHVyZV9jaGFubmVsX2FjdGlvbnMiOnRydWUsImZlYXR1cmVfc2NyZWVuX3NoYXJlX25lZWRzX2Flcm8iOmZhbHNlLCJmZWF0dXJlX2Vtb2ppX2J5X2lkIjp0cnVlLCJmZWF0dXJlX2NoYW5uZWxfaW52aXRlX3Rva2VuaXphdGlvbiI6dHJ1ZSwiZmVhdHVyZV9lbWFpbF9ub3RpZnkiOmZhbHNlLCJmZWF0dXJlX2ltcHJvdmVkX2VtYWlsX3JlbmRlcmluZyI6dHJ1ZSwiZmVhdHVyZV9taW5pX2Jyb3dzZXJfdHJhbnNsYXRpb25zIjpmYWxzZSwiZmVhdHVyZV91bmZ1cmxfbWV0YWRhdGEiOmZhbHNlLCJmZWF0dXJlX3BhcGVyY2xpcF9jb2FjaG1hcmtfZXhwZXJpbWVudHMiOnRydWUsImZlYXR1cmVfcGx1c19tZW51X2FkZF9hcHBzX2xpbmsiOmZhbHNlLCJmZWF0dXJlX3JlY2VudF9maWxlc19vbW5pcGlja2VyIjpmYWxzZSwiZmVhdHVyZV9yZWNlbnRfZGVza3RvcF9maWxlcyI6dHJ1ZSwiZmVhdHVyZV9odWRkbGVzX2kxOG4iOmZhbHNlLCJmZWF0dXJlX2Nvbm5lY3RfZGVlcGxpbmsiOmZhbHNlLCJmZWF0dXJlX2NlYV9hbGxvd2xpc3RfY2hhbmdlcyI6ZmFsc2UsImZlYXR1cmVfY2VhX2NoYW5uZWxfbWFuYWdlbWVudCI6dHJ1ZSwiZmVhdHVyZV9jZWFfYWRtaW5fY29udHJvbHMiOmZhbHNlLCJmZWF0dXJlX2NlYV9hbGxvd2xpc3RfY2hhbmdlc19wbHVzIjpmYWxzZSwiZmVhdHVyZV9pYV9sYXlvdXQiOnRydWUsImZlYXR1cmVfbWlzY19pYV9hMTF5X3RyYW5zbGF0aW9ucyI6ZmFsc2UsImZlYXR1cmVfdGhyZWFkZWRfY2FsbF9ibG9jayI6ZmFsc2UsImZlYXR1cmVfZW50ZXJwcmlzZV9tb2JpbGVfZGV2aWNlX2NoZWNrIjp0cnVlLCJmZWF0dXJlX25ld19jb3B5X2Zvcl9pZGVudGl0eV9iYXNpYyI6ZmFsc2UsImZlYXR1cmVfdHJhY2Vfd2ViYXBwX2luaXQiOnRydWUsImZlYXR1cmVfdHJhY2VfanFfaW5pdCI6dHJ1ZSwiZmVhdHVyZV9zZXZlbl9kYXlzX2VtYWlsX3VwZGF0ZSI6dHJ1ZSwiZmVhdHVyZV91YWVfdGF4X2lkX2NvbGxlY3Rpb24iOnRydWUsImZlYXR1cmVfcXVlYmVjX3RheF9pZF9jb2xsZWN0aW9uIjp0cnVlLCJmZWF0dXJlX3F1ZWJlY190YXhfYXNzZXNzbWVudCI6dHJ1ZSwiZmVhdHVyZV9nZW9yZ2lhX3RheF9pZF9jb2xsZWN0aW9uIjp0cnVlLCJmZWF0dXJlX2dlb3JnaWFfdGF4X2Fzc2Vzc21lbnQiOnRydWUsImZlYXR1cmVfbGllY2h0ZW5zdGVpbl90YXhfaWRfY29sbGVjdGlvbiI6dHJ1ZSwiZmVhdHVyZV9saWVjaHRlbnN0ZWluX3RheF9hc3Nlc3NtZW50Ijp0cnVlLCJmZWF0dXJlX2tzYV90YXhfaWRfY29sbGVjdGlvbiI6dHJ1ZSwiZmVhdHVyZV9pbmRvbmVzaWFfdGF4X2NoYW5nZV9ub3RpZmljYXRpb24iOmZhbHNlLCJmZWF0dXJlX2luZG9uZXNpYV90YXhfYXNzZXNzbWVudCI6ZmFsc2UsImZlYXR1cmVfY2hhbm5lbF9zZWN0aW9ucyI6dHJ1ZSwiZmVhdHVyZV9jaGFubmVsX3NlY3Rpb25zX3NpZGViYXJfYmVoYXZpb3JfdWkiOmZhbHNlLCJmZWF0dXJlX21pZ3JhdGVfZ29vZ2xlX2RpcmVjdG9yeV9hcGlzIjp0cnVlLCJmZWF0dXJlX3Nob3dfZW1haWxfZm9yd2FyZGVkX2J5IjpmYWxzZSwiZmVhdHVyZV9kb3dubG9hZF9maW5kZXJfdXBkYXRlIjp0cnVlLCJmZWF0dXJlX3NoYXJlX21vZGFsX2RpYWxvZyI6dHJ1ZSwiZmVhdHVyZV9ibG9ja19maWxlc19lc2MiOnRydWUsImZlYXR1cmVfaW52aXRlX25ld19lcnJvciI6dHJ1ZSwiZmVhdHVyZV9tcGRtX2F1ZGllbmNlX2V4cGFuc2lvbiI6dHJ1ZSwiZmVhdHVyZV94d3NfdXNlcl9ncm91cHNfc2VsZWN0b3IiOnRydWUsImZlYXR1cmVfYWNjZXNzaWJsZV9kYXRlX3BpY2tlcl9zZWxlY3QiOmZhbHNlLCJmZWF0dXJlX3JlbW92ZV9lbWFpbF9wcmV2aWV3X2xpbmsiOnRydWUsImZlYXR1cmVfZGVza3RvcF9lbmFibGVfdHNsb2ciOmZhbHNlLCJmZWF0dXJlX2Rlc2t0b3BfZW5hYmxlX3N0aWNreV9ub3RpZmljYXRpb25fcHJlZiI6ZmFsc2UsImZlYXR1cmVfbnRsbV9kb21haW5fYXBwcm92YWxfdWkiOmZhbHNlLCJmZWF0dXJlX2VtYWlsX2RldGVybWluZV9jaGFyc2V0Ijp0cnVlLCJmZWF0dXJlX3dpbmRvd3M3X2RlcHJlY2F0aW9uIjp0cnVlLCJmZWF0dXJlX3dpbmRvd3M3X2RlcHJlY2F0aW9uX21vZGFsIjpmYWxzZSwiZmVhdHVyZV9ub19kZXByZWNhdGlvbl9pbl91cGRhdGVyIjpmYWxzZSwiZmVhdHVyZV91c2VyX3ByZWZlcnNfcGF1c2VkX2FuaW1hdGlvbnMiOnRydWUsImZlYXR1cmVfZXpfc3Vic2NyaWJlX3ZfMV9zdGFnZV8wIjpmYWxzZSwiZmVhdHVyZV9wZWFfZG9tYWluX2FsbG93bGlzdCI6dHJ1ZSwiZmVhdHVyZV9jb21wb3Nlcl9hdXRoX2FkbWluIjp0cnVlLCJmZWF0dXJlX3VrcmFpbmVfdGF4X2lkX2NvbGxlY3Rpb24iOnRydWUsImZlYXR1cmVfdWtyYWluZV90YXhfYXNzZXNzbWVudCI6dHJ1ZSwiZmVhdHVyZV9oZXJtZXNfanVzdF9pbl90aW1lX2F1dGgiOnRydWUsImZlYXR1cmVfdGFpd2FuX3RheF9pZF9jb2xsZWN0aW9uIjp0cnVlLCJmZWF0dXJlX3VrX2V1X3RheF9pZF9jb2xsZWN0aW9uIjp0cnVlLCJmZWF0dXJlX3VrX2V1X3RheF9hc3Nlc3NtZW50Ijp0cnVlLCJmZWF0dXJlX3J1X2RlcHJlY2F0aW9uIjp0cnVlLCJleHBlcmltZW50X2Fzc2lnbm1lbnRzIjp7InNzcF9taWdyYXRpb25faGlnaGxpZ2h0ZXIiOnsiZXhwZXJpbWVudF9pZCI6IjUxNjMwNTEyNDU4MjYiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4NDMyMTE4MCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwibWFya2V0aW5nX2NhY2hlX2NhcmVlcnMiOnsiZXhwZXJpbWVudF9pZCI6IjUxNTMwNDE3NDUwMTQiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4NDM5NTg3NywibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic2tpcF9zdXBlcmNvb2tpZV9yb3RhdGVfd2hlbl9yZW1vdmVkIjp7ImV4cGVyaW1lbnRfaWQiOiI1MjM5NDQ4MDM1MjA1IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6Imhhc2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjg0Mjg0ODkxLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJnYW50cnlfYXV0aF9nZXRjb29raWV1c2Vyc19yZXBsYWNlbWVudCI6eyJleHBlcmltZW50X2lkIjoiNDgxNjA1MjM5ODY3NSIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjgyMzY0NTQyLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJjb250YWN0X3NhbGVzX3V4Ijp7ImV4cGVyaW1lbnRfaWQiOiI0OTgwMjE4MTU3NjQ4IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6ImNvbnRyb2wiLCJ0cmlnZ2VyIjoiaGFzaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Nzk2NzkxMTgsImxvZ19leHBvc3VyZXMiOnRydWUsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiY3VzdG9tZXJfYXdhcmRzX2kxOG5fMjAyMyI6eyJleHBlcmltZW50X2lkIjoiNTIzMTQ3MDA1MDk5OCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjgzNzU5NjUwLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJzdGF0ZV9vZl93b3JrX3d0bnkiOnsiZXhwZXJpbWVudF9pZCI6IjUxNzQyOTE5MzA0NzAiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4MzgyOTUyMSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiYWN0aXZhdGlvbl9icm93c2VyX2RlcHJlY2F0aW9uX3dhcm5pbmdfYXByaWxfMjAyMyI6eyJleHBlcmltZW50X2lkIjoiNTAyMDU4ODExNDkxNyIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjgyOTYxMzc4LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJleHBhbmRlZF9uYXZfZGVza3RvcCI6eyJleHBlcmltZW50X2lkIjoiNDk4NTg3MTk2NzM3OCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJ0cmVhdG1lbnQiLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4MjYzNzk4NSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiY3VzdF9hY3FfYWlfbWVzc2FnaW5nX2hwIjp7ImV4cGVyaW1lbnRfaWQiOiI1MTQ3OTUwMDU1NjIxIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6InRyZWF0bWVudCIsInRyaWdnZXIiOiJoYXNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4Mjk4MDU0MSwibG9nX2V4cG9zdXJlcyI6dHJ1ZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJhdXRoX2NyZWRlbnRpYWxfY3JlYXRlX2NyZWRlbnRpYWxzIjp7ImV4cGVyaW1lbnRfaWQiOiI0ODk4NzMzMzQ3MzE2IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2ODEzOTM5NDEsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImN1c3RfYWNxX2hvbWVwYWdlX2N1c3RvbWVyX3N0b3JpZXMiOnsiZXhwZXJpbWVudF9pZCI6IjUwNjI5MjA5MzkzNDQiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4MjQ2Mjg4MCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic3NwX21pZ3JhdGlvbl9saW5rc2FmZXR5Ijp7ImV4cGVyaW1lbnRfaWQiOiI1MDUwNDgyNTkyMTk4IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2ODA2Nzk4NDQsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImNhc3VhbF90ZXN0Ijp7ImV4cGVyaW1lbnRfaWQiOiIzMjQ5ODczODE5NzAyIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6InRyZWF0bWVudCIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjgyMTAzODgzLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJzaWduaW5fbG9nb3V0X3Nlc3Npb25faWRfcmVxdWlyZWQiOnsiZXhwZXJpbWVudF9pZCI6IjUwNjA0NzI3OTE1MDciLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY4MTE0NzQyOCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic3NwX21pZ3JhdGlvbl90d2l0dGVyc3ViIjp7ImV4cGVyaW1lbnRfaWQiOiI1MDc2OTc0OTQ3NDc5IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2ODEzMTIyNTUsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm1yaXNfdXNlcmNyZWF0b3JfbGl2ZSI6eyJleHBlcmltZW50X2lkIjoiNDkyMTc4MDE3NTQ0NCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjgwMTA3NzE5LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJuZXd4cF84NTUwIjp7ImV4cGVyaW1lbnRfaWQiOiI0NzU4NDY0OTEzNDU2IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Nzk2MDQ4MzYsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm5ld3hwXzg3NjAiOnsiZXhwZXJpbWVudF9pZCI6IjQ5OTI1NjAxMzcyOTciLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3OTU5MTc1MSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic3NwX21pZ3JhdGlvbl9tYWdpY2FsaW1hZ2VzcmVxdWVzdCI6eyJleHBlcmltZW50X2lkIjoiNDkxNTc4MTUzNTI0OSIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc4OTU0NzI3LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJjdXN0b21lcl9hd2FyZHNfbGF1bmNoIjp7ImV4cGVyaW1lbnRfaWQiOiIyNjczNTQ4NDExMTU1IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImZpbmlzaGVkIiwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwicHhwMTEzNF92aXNpdG9yIjp7ImV4cGVyaW1lbnRfaWQiOiI0OTM1NzEzMjQwNzI0IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Nzk1OTE0ODgsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInVtc2Ffd29ya3NwYWNlX2NyZWF0aW9uX3RuYyI6eyJleHBlcmltZW50X2lkIjoiNDk4MDQyODg1NTg0NCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc5MzM0ODU2LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJuZXd4cF84MzA3Ijp7ImV4cGVyaW1lbnRfaWQiOiI0NDUyNzg3MDc2MTM1IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzkzMjQ4NjYsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm1hcmtldGluZ191bXNhIjp7ImV4cGVyaW1lbnRfaWQiOiI0OTIyMDAwMTA4MTk2IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzkzMTc0NzIsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm1yaXNfZXh0ZW5zaW9uIjp7ImV4cGVyaW1lbnRfaWQiOiI0NzQ2MjA2OTQ3MzY1IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzkwOTM0NjMsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImNvbm5lY3Rfb3BlbmFpX3N0b3J5Ijp7ImV4cGVyaW1lbnRfaWQiOiI0OTQwMDc4NTk3MjQ5IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Nzg0ODYzMjQsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImRhdGFfbWFuYWdlbWVudF9idWxsZXQiOnsiZXhwZXJpbWVudF9pZCI6IjQ5MTE5MjcwMDExNDIiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3ODQwMTEwMSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic29sdXRpb25zX3RlY2hub2xvZ3lfbHAiOnsiZXhwZXJpbWVudF9pZCI6IjQ2OTMzMTk3MTA5MTUiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3NzA5MDkyOSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiaXJlbGFuZF9hZGRyZXNzXzIwMjMiOnsiZXhwZXJpbWVudF9pZCI6IjQ4ODg0MDQzOTE5NTUiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3ODEzNDczOSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic2xhY2tfaWVfYWRkcmVzcyI6eyJleHBlcmltZW50X2lkIjoiNDg1Nzg0OTc0ODc1NCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc3NzkzMzk2LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJjcnlwdG9fc2lkZWNhcl9kYXJrX21vZGVfdmlzaXRvciI6eyJleHBlcmltZW50X2lkIjoiNDgzODczNzU1NTI4MiIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc3MDg2MDA4LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJtYXJrZXRpbmdfc3hzdyI6eyJleHBlcmltZW50X2lkIjoiNDgyMTU2NTg2NjI4OCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc3MjcxNDc4LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJhY3RpdmF0aW9uX2Jyb3dzZXJfZGVwcmVjYXRpb25fd2FybmluZ19mZWJydWFyeV8yMDIzIjp7ImV4cGVyaW1lbnRfaWQiOiI0NzU5ODA0OTQ2MzA0IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzYzMTIyODYsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm5ld3hwXzg1MzQiOnsiZXhwZXJpbWVudF9pZCI6IjQ3MjQ5MTQ5OTQ2MjUiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3NTk3NjUwMiwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic3NwX21pZ3JhdGlvbl90aW1lcnNlcnZpY2UiOnsiZXhwZXJpbWVudF9pZCI6IjQ3NTk3MDQwNDAxNDkiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3NTkzMjk2NywibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwibG9naW5fY2hlY2tfbG9naW5fdmFsaWRhdGUiOnsiZXhwZXJpbWVudF9pZCI6IjQ2ODMyMjkyMjE1NjkiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoiZmluaXNoZWQiLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJhY3RpdmF0aW9uX2Jyb3dzZXJfZGVwcmVjYXRpb25fcmVkX2Jhbm5lcl9tYXJjaF8yMDIzIjp7ImV4cGVyaW1lbnRfaWQiOiI0MjQ2Njc5NTA5ODU4IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzYzOTUzNTYsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm9uMjRfZXh0ZW5zaW9uIjp7ImV4cGVyaW1lbnRfaWQiOiI0NzcyMDE5ODI0MjExIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzU4OTE1OTUsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInNzcF9taWdyYXRpb25fYXBwbGluayI6eyJleHBlcmltZW50X2lkIjoiNDM0MDkyNDE0MDk5NCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjc1NzA1NTQwLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJtYXJrZXRpbmdfYWxsb3dfZXZlbnRzX2tvX2tyIjp7ImV4cGVyaW1lbnRfaWQiOiI0NjIyMTU0Mjk1NDYzIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzQ3MDU2MDgsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInVpX2dlbl9ibG9nX2FuZF9yZXNvdXJjZXMiOnsiZXhwZXJpbWVudF9pZCI6IjQ2NDg1ODI1ODgyNjMiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY3NDY4NDk0OSwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiaW50ZWdyaXR5X3Jlc19sZWdhY3lfb3JfbmV3Ijp7ImV4cGVyaW1lbnRfaWQiOiIzODY1Njc0ODA2ODg2IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NjAwMjk5NTEsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInByb2pfYnJhbmRfY3VzdG9tZXJfc3Rvcmllc19scCI6eyJleHBlcmltZW50X2lkIjoiMzQ0ODAyMTM4MDQ0OCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjUzNTk2MTI3LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJncmJfdl8yIjp7ImV4cGVyaW1lbnRfaWQiOiI0MzIxNzMwMTI2OTY0IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NzA1MzgwMTAsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInNzcF9taWdyYXRpb25fdHJhY2UiOnsiZXhwZXJpbWVudF9pZCI6IjQyNjA4OTU3NjM1MTAiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY2OTIyNTkzNiwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwicHJvbW9fcGFydG5lcnNfcmVib290Ijp7ImV4cGVyaW1lbnRfaWQiOiI0Mjc0MTU0OTI2MzkwIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Njg3MjQwNjYsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImRlbnlfcnVzc2lhbl9pcCI6eyJleHBlcmltZW50X2lkIjoiMzIwMTA1MTE1Mzk4OSIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjQ3OTU4MDIyLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJkZV9iYW5uZXJfbm92XzIyIjp7ImV4cGVyaW1lbnRfaWQiOiI0MjgxMzM1NDkzNTM4IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2Njc0OTI5NTgsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sIm5ld3hwX2Nvb2tpZXMiOnsiZXhwZXJpbWVudF9pZCI6IjkxMDE3NDU4NDMwNyIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJkZWR1cGVfdGVhbXMiLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTU4MDIzNTkyNiwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiZ292c2xhY2tfcHJvdmlzaW9uX2Jsb2NrIjp7ImV4cGVyaW1lbnRfaWQiOiIzMjg5NDgyNzg4NTAxIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NTA5OTAwNzIsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImdyYl9scCI6eyJleHBlcmltZW50X2lkIjoiNDA5NDEyNzEyNjA5NyIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjYzODc4MjU5LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJkaHFfaHVkZGxlc19kcmVhbWZvcmNlX2xhdW5jaCI6eyJleHBlcmltZW50X2lkIjoiMzk4NDM3OTM2Njk4MyIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJ0cmVhdG1lbnQiLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY2MzY3NjI3OCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwicHhwMjE0XzJfdiI6eyJleHBlcmltZW50X2lkIjoiMzU4MzYzMzk2NjAwNiIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjYyMDM3NDg2LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJkaWdpdGFsX2hxX2xhdW5jaCI6eyJleHBlcmltZW50X2lkIjoiMjUwNjkxNjkzNTY4NCIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJvbiIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjMyMjI2NDg5LCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJhY3Rfam9pbmVyX2RlbGlnaHQiOnsiZXhwZXJpbWVudF9pZCI6IjM5MDQ5MTU2MzQxNDUiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY2MDk1MDAyOCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiaW50ZWdyaXR5X2NoZWNrX3RlYW1fY3JlYXRpb25fYmxvY2tpbmdfYmxvY2tsaXN0c19vbmx5Ijp7ImV4cGVyaW1lbnRfaWQiOiIzODE5NjY5MTQ4NTgyIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2NTg5NDM3MTgsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImludGVncml0eV9jaGVja190ZWFtX2NyZWF0aW9uX25vbmJsb2NraW5nX3Zpc2l0b3IiOnsiZXhwZXJpbWVudF9pZCI6IjM3NTEzMTg3NDM0NzMiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY1NjU0NTQyMywibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwic2VhcmNoX3pkX3ZzX3NvbHIiOnsiZXhwZXJpbWVudF9pZCI6IjEzNTU3MDkwMDIxNDUiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoiY29udHJvbCIsInRyaWdnZXIiOiJmaW5pc2hlZCIsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sInNsYWNrX2Nvbm5lY3Rfc2tpcF90ZWFtX25hbWVfdmlzaXRvcl9leHBlcmltZW50Ijp7ImV4cGVyaW1lbnRfaWQiOiIyMTU4OTk5MjM5NzI5IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6InRyZWF0bWVudCIsInRyaWdnZXIiOiJmaW5pc2hlZCIsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImRpZ2l0YWxfZmlyc3RfbGlnaHRuaW5nX3N0cmlrZV9jdXN0YWNxIjp7ImV4cGVyaW1lbnRfaWQiOiIyMjIwNjYwNjc5MzY0IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2MjUwNzU1NjMsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImN1c3RfYWNxX3BhcnRuZXJzX3RlbXBsYXRlIjp7ImV4cGVyaW1lbnRfaWQiOiIyMjMyMjA0NTUxNTA0IiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6InRyZWF0bWVudCIsInRyaWdnZXIiOiJsYXVuY2hfdmlzaXRvciIsInNjaGVkdWxlX3RzIjoxNjI4MTkxNDEwLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJjb21tdW5pdHlfbGF1bmNoIjp7ImV4cGVyaW1lbnRfaWQiOiIyNjUyODQxNTc2MzczIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6Im9uIiwidHJpZ2dlciI6ImxhdW5jaF92aXNpdG9yIiwic2NoZWR1bGVfdHMiOjE2MzU4NzExNDcsImxvZ19leHBvc3VyZXMiOmZhbHNlLCJleHBvc3VyZV9pZCI6ImY2YjQyOTE1Nzg2MmViZjc0MWEyMmQxOWQxMjJmNmZmIn0sImFwaWRvY3NfZl9wdWJsaWMiOnsiZXhwZXJpbWVudF9pZCI6IjI3MjMyNDAyNjE5MDgiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTYzNzAyNzAxMCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiaGNfaWRlYXNfdGVtcGxhdGVzX3NlY3Rpb24iOnsiZXhwZXJpbWVudF9pZCI6IjI4NjE4NDkzODE3OTciLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoibGF1bmNoX3Zpc2l0b3IiLCJzY2hlZHVsZV90cyI6MTY0MDExNzE1NCwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiYXBwX2RpcmVjdG9yeV9hd3NfcHJvbW90aW9uX2Jhbm5lciI6eyJleHBlcmltZW50X2lkIjoiMzAyNTM5Nzc4MTA3MyIsInR5cGUiOiJ2aXNpdG9yIiwiZ3JvdXAiOiJjb250cm9sIiwidHJpZ2dlciI6ImZpbmlzaGVkIiwibG9nX2V4cG9zdXJlcyI6ZmFsc2UsImV4cG9zdXJlX2lkIjoiZjZiNDI5MTU3ODYyZWJmNzQxYTIyZDE5ZDEyMmY2ZmYifSwiYXBwX2RpcmVjdG9yeV9wYXJ0bmVyX3Byb21vdGlvbl9iYW5uZXJzIjp7ImV4cGVyaW1lbnRfaWQiOiIzMDA5NDU4MTQ1ODkzIiwidHlwZSI6InZpc2l0b3IiLCJncm91cCI6ImNvbnRyb2wiLCJ0cmlnZ2VyIjoiZmluaXNoZWQiLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9LCJzc2JfZmlyc3Rfc2hvd190ZWFtX25hbWUiOnsiZXhwZXJpbWVudF9pZCI6IjM1MTE5MTg3MDQwMDMiLCJ0eXBlIjoidmlzaXRvciIsImdyb3VwIjoib24iLCJ0cmlnZ2VyIjoiZmluaXNoZWQiLCJsb2dfZXhwb3N1cmVzIjpmYWxzZSwiZXhwb3N1cmVfaWQiOiJmNmI0MjkxNTc4NjJlYmY3NDFhMjJkMTlkMTIyZjZmZiJ9fSwibm9fbG9naW4iOmZhbHNlfTs8L3NjcmlwdD48c2NyaXB0IHR5cGU9InRleHQvamF2YXNjcmlwdCIgY3Jvc3NvcmlnaW49ImFub255bW91cyIgc3JjPSJodHRwczovL2Euc2xhY2stZWRnZS5jb20vYnYxLTEwL3ByaW1lci12ZW5kb3IuZjJlMjhmYy5wcmltZXIubWluLmpzIiBvbmxvYWQ9IndpbmRvdy5fY2RuID8gX2Nkbi5vayh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgb25lcnJvcj0id2luZG93Ll9jZG4gPyBfY2RuLmZhaWxlZCh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCI+PC9zY3JpcHQ+PHNjcmlwdCB0eXBlPSJ0ZXh0L2phdmFzY3JpcHQiIGNyb3Nzb3JpZ2luPSJhbm9ueW1vdXMiIHNyYz0iaHR0cHM6Ly9hLnNsYWNrLWVkZ2UuY29tL2J2MS0xMC9sb2dpbi1jb3JlLmQ0ZjFjYmYucHJpbWVyLm1pbi5qcyIgb25sb2FkPSJ3aW5kb3cuX2NkbiA/IF9jZG4ub2sodGhpcywgYXJndW1lbnRzKSA6IG51bGwiIG9uZXJyb3I9IndpbmRvdy5fY2RuID8gX2Nkbi5mYWlsZWQodGhpcywgYXJndW1lbnRzKSA6IG51bGwiPjwvc2NyaXB0PjxsaW5rIGhyZWY9Imh0dHBzOi8vYS5zbGFjay1lZGdlLmNvbS9idjEtMTAvbG9naW4tY29yZS43Njg4MmNjLnByaW1lci5taW4uY3NzIiByZWw9InN0eWxlc2hlZXQiIHR5cGU9InRleHQvY3NzIiBvbmxvYWQ9IndpbmRvdy5fY2RuID8gX2Nkbi5vayh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgb25lcnJvcj0id2luZG93Ll9jZG4gPyBfY2RuLmZhaWxlZCh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgY3Jvc3NvcmlnaW49ImFub255bW91cyI+PGxpbmsgaHJlZj0iaHR0cHM6Ly9hLnNsYWNrLWVkZ2UuY29tLzNiODE3MDkvc3R5bGUvcm9sbHVwLXNsYWNrX2tpdF9iYXNlLmNzcyIgcmVsPSJzdHlsZXNoZWV0IiBpZD0ic2xhY2tfa2l0X2hlbHBlcnMiIHR5cGU9InRleHQvY3NzIiBvbmxvYWQ9IndpbmRvdy5fY2RuID8gX2Nkbi5vayh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgb25lcnJvcj0id2luZG93Ll9jZG4gPyBfY2RuLmZhaWxlZCh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgY3Jvc3NvcmlnaW49ImFub255bW91cyI+PGxpbmsgaHJlZj0iaHR0cHM6Ly9hLnNsYWNrLWVkZ2UuY29tLzBiOWQyZmMvc3R5bGUvcm9sbHVwLXNsYWNrX2tpdF9oZWxwZXJzLmNzcyIgcmVsPSJzdHlsZXNoZWV0IiBpZD0ic2xhY2tfa2l0X2hlbHBlcnMiIHR5cGU9InRleHQvY3NzIiBvbmxvYWQ9IndpbmRvdy5fY2RuID8gX2Nkbi5vayh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgb25lcnJvcj0id2luZG93Ll9jZG4gPyBfY2RuLmZhaWxlZCh0aGlzLCBhcmd1bWVudHMpIDogbnVsbCIgY3Jvc3NvcmlnaW49ImFub255bW91cyI+Cgo8IS0tIHNsYWNrLXd3dy1oaHZtLW1haW4taWFkLWxpb2svIDIwMjMtMDUtMTggMTA6MTY6MDgvIHY1NGJkMzE2MmZhODUwYzNkOWI3MzVjNDg2ODgwMWUzMDZhZGIxZGRkLyBCOkggLS0+Cgo8L2JvZHk+PC9odG1sPg==
## Scope

log of decisions reducing or adding time to the scope
* Kafay Ng [2023-04-26T20:54:16.174Z]

Message: Buenas tardes, unas notas sobre la reu que acabamos de tener entre Rodrigo Nunez y yo
• Manejo de token para git: se va a utilizar el método de crear un token con un usuario nuevo (dependiendo del cliente) o que un integrante creé el token. Este token tiene la posibilidad de no experirar entonces quedará a disposición del proyecto/cliente
• Manejo de los repositorios: los repositorios van a tener únicamente los md files del proyecto con la información (scopes, requirements, teams, etc…) por lo que se van a clonar los repositorios a nivel de codigo y se van a mantener en memoria en vez de borrarlos una vez terminado el proceso de edición -&gt; git add -&gt; git commit -&gt; git push -&gt; merge
• Buscar un módulo para la escritura de archivos que maneje la inserción en lugares específicos de un archivo para poder evitar tener un buffer de un antes del string a insertar y un después del string a insertar y hacerles join a un solo string grande.

Notes: Kafay explained the new scope after meeting with Nuñez

#### **Ixel Castro Richard [2023-05-12T21:30:18.955Z]** 

Message: <https://github.com/akurey/AK-Slack-App#add-akurey-source-application-to-the-channels-on-slack>

Notes: Update

#### **Jose Andrés Barboza González [2023-05-16T20:38:21.228Z]** 

Message: y ojo la vara

Notes: Holi

#### **Ixel Castro Richard [2023-05-16T21:30:07.084Z]** 

Message: Sí

Notes: QA Test

#### **Ixel Castro Richard [2023-05-16T21:43:50.210Z]** 

Message: Slack Test

Notes: Update

#### **Ixel Castro Richard [2023-05-17T15:29:23.666Z]** 

Message: Listo, también le faltó un permiso al ambiente de QA para escribir a channels

Notes: Update

## Notes

log of project notes 


#### **Kafay Ng [2023-05-12T15:24:25.127Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation for fofo

#### **Ixel Castro Richard [2023-05-12T17:22:09.523Z]** 

Message: <https://github.com/akurey/AK-Projects-Single-Source>

Notes: Update

#### **Ixel Castro Richard [2023-05-17T00:58:05.126Z]** 

Message: Slack Test

Notes: Update

#### **Ixel Castro Richard [2023-05-17T14:36:58.090Z]** 

Message: Ese es un channel privado que cree para eso

Notes: Update

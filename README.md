

# Grow it: REST-API-Server

## Target  
REST API server designed for Grow it application.

------------------

## Description
Global information is detailed in app repository: [Grow it](https://github.com/csd0/Grow.it)


## API  reference  

|    Method   |  HTTP request  |  Description  |
|------------|-----------------|-----------------|
| login | post /login |JWT authentication | 
| list | get /users | list all users | 
| create | post /user | creates a user | 
| update | put /user/:_id | updates a user | 
| delete | delete /user/:_id | deletes a user | 
| retrieve | get /user/:_id | retrieves a user | 
| searchUser | get /userq/:query | search users matching query | 
| listOrchard | get /orchards | list all orchards | 
| createOrchard | post /orchard | creates an orchard | 
| updateOrchard | put /orchard/:_id | updates an orchard | 
| deleteOrchard | delete /orchard/:_id | deletes an orchard | 
| retrieveOrchard | get /orchard/:_id | retrieves an orchard | 
| searchOrchard | post /orchardq | search orchards matching query | 
| addCollaborator | post /orchard/addcollaborator | relates collaborator with an orchard | 
| deleteCollaborator | post /orchard/deletecollaborator| delete collaborator from an orchard | 
| addPlantation | post /orchard/addplantation | add plantation to an orchard | 
| deletePlantation | post /orchard/deleteplantation | deletes plantation from an orchard | 
| updatePlantation | post orchard/updateplantation | updates plantation from an orchard  | 
| getUsersByOrchard | get /orchard/populateusers/:orchardid | populate users data related specific orchard | 

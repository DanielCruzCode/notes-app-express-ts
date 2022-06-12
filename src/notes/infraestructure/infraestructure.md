# Infraestructure

This folder contains the infraestructure files, this sounds abstract, but it
refers to connect to any part related with infraestructure, the controllers
intercept a request via endpoints built on any framework or library and the
request can be controlated with many proccess. The Database is part of
infraestructure for example

NoteGetController
NotePostController
MySqlNoteRepository -> extends of NoteRepository interface created in domain layer

<<<<<<< HEAD
Readme
=======
#Description
Airbnb clone is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.
The project currently only implements the back-end console.

#Classes 
AirBnB utilizes the following classes:
BaseModel FileStorage User State City Amenity Place Review PUBLIC INSTANCE ATTRIBUTES id created_at updated_at Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel Inherits from BaseModel PUBLIC INSTANCE METHODS save to_dict all new save reload "" "" "" "" "" "" PUBLIC CLASS ATTRIBUTES email password first_name last_name name state_id name name city_id user_id name description number_rooms number_bathrooms max_guest price_by_night latitude longitude amenity_ids place_id user_id text PRIVATE CLASS ATTRIBUTES file_path objects 
#Storage 
The above classes are handled by the abstracted storage engine defined in the FileStorage class.
Every time the backend is initialized, AirBnB instantiates an instance of FileStorage called storage. 
The storage object is loaded/re-loaded from any class instances stored in the JSON file file.json. 
As class instances are created, updated, or deleted, the storage object is used to register corresponding changes in the file.json.

#Console 
The console is a command line interpreter that permits management of the backend of AirBnB. It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the storage object defined above).
Using the Console The AirBnB console can be run both interactively and non-interactively. 
To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.
>>>>>>> c0a5b15d537fbf25cd95e332ee0a61b6d31c4f5f

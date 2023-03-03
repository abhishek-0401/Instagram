# Instagram

- ## Frameworks and Language used
  - #### Spring Boot Framework
  - #### Java language
- ## Data Flow
  - ### UserController
     - ##### _saveUser( )_   
     - ##### _getUser( )_       
     - ##### _deleteUser( )_     
     - ##### _updateUser( )_  
     
  - ### PostController
     - ##### _savePost( )_   
     - ##### _getPost( )_       
     - ##### _deletePost( )_     
     - ##### _updatePost( )_     
    
  - ### UserService
     - ##### _saveUser( )_      - saves a new user to the tbl_user table
     - ##### _getUser( )_       - gets users list if the request parameter is null
     - ##### _deleteUser( )_     - deletes user and all the posts posted by him
     - ##### _updateUser( )_     - updates user info
     
   - ### PostService
     - ##### _savePost( )_      - saves a new post to the tbl_post table
     - ##### _getPost( )_       - gets posts list by a perticular user and if postId is not specified, it will get all the posts
     - ##### _deletePost( )_    - deletes a particular post
     - ##### _updatePost( )_    - updates a post whose postId will be given
    
   - ### Repository
     - ##### _findAll( )_   
     - ##### _findById( )_          
     - ##### _deleteById( )_  
     - ##### _save( )_
     
- ## Database Used
  - #### MySQL Database :  instagram_db
  
- ## Project Summary
  In this project we have created 2 models namely;User and Post. We have provided some endpoints and also in this section below we have given our API. Using this API we can perform the CRUD operations accordingly.
  
  
  > http://localhost:8080
  
  End Points:
    - ##### /user     
    for creating and getting user
    - ##### /user/{userId}      
    for updating and deleteing user
    - ##### /post     
    for creating and getting post
    - ##### /post/{postId}      
    for updating and deleting post
 

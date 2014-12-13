# What this software must do  

Team Andromedus  

Alexis Hoshino, Eric Tian, HQ Pham-Nguyen, Kathleen Enverga  

## Assumptions

The user will have:
+ an intention to contribute to or create memorials
+ a Facebook account + a browser that supports HTML5 and JavaScript + an internet capable device  

## Functional requirements

#### General

+ log in Facebook users 
+ have memorial owner (referred to as the “steward”, who is a Facebook user) invite other Facebook users to contribute to the memorial.
+ accept/reject invitations for memorial contribution.
	- invitations will have one of three statuses: accepted, rejected, or pending
+ download the Facebook data (photos, posts, comments, likes) of the deceased.

#### Memorial Contributions

+ add/remove/edit/view stories
+ add/remove/edit/view deceased’s information (i.e. date of death, epitaph, steward name, and name of the deceased)
+ upload content from local drive

### User account requirements

#### User

+ be able to create a memorial (which would make this user a “steward” of that memorial)
+ be able to view a memorial they are a collaborator on
+ be able to contribute content within a memorial (e.g. text post)
+ be able to invite other contributors

##### User (Steward)

+ be able to remove a memorial they administer
+ be able to view a list of other collaborators of a memorial they administer
+ be able to remove a collaborator from a memorial they administer
+ be able to finalize a memorial they administer
+ be able to delete a memorial they administer

### Technology requirements

+ CSS - Bootstrap
+ Vagrant
+ Laravel Framework
+ MySQL
+ PHP
+ Git
+ Pagoda

## Non-functional requirements 

+ The application should not be depressing or difficult for the user to use, especially in a time of grief
+ The application should provide a positive experience to help those in grief find peace
+ The application and features must be sensitive to our intended audience.
+ accessible on a mobile device
+ Easy to use
+ Retrieve Facebook data quickly.


# MVC_Observer
Java project - MVC arhitectural design pattern with behavioral design pattern Observer.

MVC Design Pattern for a Cake Shops management system using Java and Swing. Using MySQL database for persistence.

Observable objects are GUIs and each component from the graphic interface is checked by the controller, from where the action is redirected to local methods.

Complex class diagram, use case with all its functions, activity and sequence diagrams.

Roles: admin and user. Admin can add to a specific cake shop, view, update, delete users. User can view, add to its workplace (cake shop), delete from it, update a cake (especially its quantity), download cake reports - JSON or CSV - if selected a cake shop - download its report.

Model - contains all model classes - Cake, CakeShop, User, etc. Controller - contains the operations associated which each object from the user interface. View - contains only fxml files which create user interface.

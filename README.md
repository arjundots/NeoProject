	Summary of approach:	
		There will be some shopping cart system where user can view the list of products, select product, apply promo code and can do the checkout process.
	
	Assumption:
		We assume that its a shopping cart system where we have to develop an application for basic shopping cart functionality.
	
	Caveats and notes:	
		We have listed products on the system on landing page. From where end user can choose the quantity of product and add them to cart. all the selected items along with quantity will be added into cart. Then User can click on cart link to view products in cart and checkout process. On this page user can apply promocode as well as can update the quantity of selected product. Upon click of checkout user will be redirected to checkout page.
    
	Steps to setup and run project on your machine:
		1. Rails framework should be installed on your machine.
		2. If you are using windows machine then you can use installer available at "http://railsinstaller.org/".
		3. Setup will automatically will setup the required paths on machine.
		4. To check if successfully install run command "ruby -v" and "rails -version".
		5. Now you can download the code from git by using following link "https://github.com/arjundots/NeoProject.git".
		6. cd to project directory "NeoProject" via command line.
		7. Create database "neos_development". Then run "rake db:migrate" command to execute migrations.
		8. Now we have to insert some data in our database tables like product. Run command "rake db:seed".
		9. We are done with app setup stuff.
		10. Run command "rails s" to run webrick server which allows to run application on browser.
		11. Now hit url http://localhost:3000 to use the application on browser.
	

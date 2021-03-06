####[16.08.2018] Task1
- Initialize project
- Create product component
- Add 'buy' button for available products, to notify about click action in console

####[20.08.2018] Task1
- Add product list service, which returns products list
- Create products list component
- Render list of products on a page
- Add cart component
- Add cart service, which returns stub list of items (not connected to real product list yet)
- Render stub items from cart service in cart component
- Render alternative block, if cart list is empty

####[21.08.2018] Task2
- Add modules for Products and Cart components, register modules in App component
- Add child Product component
- Realize parent-child communication withing Product List component
- Add link 'Show/Hide' to toggle product description visibility. Apply directive to prevent default link click behaviour.

####[22.08.2018] Task2
- Implement parent-child communication via template variable. Access DOM element and set 'App Title' from component class.
- Implement siblings communication via Communication Service. Use observable subscription to listen, when product is added to cart.
- Add hover style directive to the Cart Item component. Use @HostBinding and @HostListener directives to control host properties and catch host events
- Use content projection to display Catalog Title element. Create catalog title text using content-child template variable.
- Add Bootstrap to the project as npm dependency. Extract global styles.

####[27.08.2018] Task2
- Move to sass
- Change some files and classes naming
- Declare communication service and shared directives in shared module

####[29.08.2018] Task3
- Add ClickStyleDirective, using ElementRef service DI, to highlight items on click

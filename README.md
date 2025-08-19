graph TD
   A((Application)) --> |Uses| D((Docker));
   D --> |Interacts with| K((Kernel));
   K --> |Manages| C((CPU));
   K --> |Manages| M((Memory));
   K --> |Manages| Dev((Devices));

Front-End : FireBase 
                ->authentication
                ->hosting
            React.js

Back-End : Node.js
                ->Express.js
                ->MongoDB            
                    ->chainStrem and Pusher for realTime Chat feature
                
            Pusher.com : a service that we will be using for real time mongodb chat 
                    "MongoDB chain tree" will be created in MongoDB that will be connected to Pusher So, Whenever changes are made in MongoDB Collections Pusher will be triggered to Push Up(Fetch) the data from MongoDB and Push Down(Update) to the Front-End , here (React.js)
            //the above is alternate to "socket.io" impl

            In fireBase realtime database was used,
                the application will be triggered when ever any changes are made.

            In MongoDB, it's to be refreshed more frequently to fetch the data from the server and deliver it to the front-End and that extra refreshing make the application very slow and waste of processing power.
        cors: "Cross-Origin Resource Sharing" is an "alternate library for HTTP-header based mechanism that allows a server to indicate any other origins (domain, shceme, or port) than its own from which a browser shoudl permit loading of resources."


UI-Structure
    
    Side_Bar    ::       Chat_Component
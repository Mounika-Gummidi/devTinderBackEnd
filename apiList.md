# devTinder API

authRouter
- POST /signup
- POST /login
- POST /logout

profileRouter
- GET /profile/view
- PATCH /profile/edit
- PATCH /profile/password

requestRouter
- POST /request/send/intrested/:userId
- POST /request/send/ignored/:userId
- POST /request/review/accepted/:requestId
- POST /request/review/rejected/:requestId

userRouter
- GET /user/requests/received
- GET /user/connections
- GET /user/feed -gets you the profiles of other users on platfrom 

status: ignore,intrested,accepted,rejected
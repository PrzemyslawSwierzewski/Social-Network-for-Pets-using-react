# Social Network for Pets using React
  This repository was created with codecademy to learn React.
# The purpose of the app
  a simple social network for pets. We able to view a pet's prifile(which contains their name, bio, and friend list)and navigate to other profiles.
# What i learned while coding this app
  To complete this project I get acquainted with the syntax of the component / this.props / this.state / JSX and a Lifecycle methods like componentDidMount / componentWillUnMount / componentDidUpdate

You can see the deployment of the app by github pages

# My work

Everything that i write in this exercise is in the Profile.js. For loading user data first i need to set this.state = { userData: null }, which represent a profile with no user data loaded. Secondly I created a method named loadUserData() that does two things: sets the userData state to null while the data is loading. and fetches the user data with fetchUserData. And for the last update the render method. For displaying user data first I created a new variable named name. If isloading is true, I set name to a sample value, such as 'Loading...'.Otherwise, I set name to this.state.userData.name. For bio/friends variable i did the exact same thing like in the name variable.

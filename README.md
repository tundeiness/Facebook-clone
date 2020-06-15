<br />
<p align="center">
  <h1 align="center">Facebook-clone</h1>

  <p align="center">
    A Ruby on Rails application
    <br />
    <br />
    <a href="https://sheltered-taiga-65616.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/pelzolga123/Facebook-clone/issues">Report Bug</a>
    ·
    <a href="https://github.com/pelzolga123/Facebook-clone/issues">Request Feature</a>
  </p>
</p>


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Features](#Features)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Contact](#Contact)
* [License](#license)
* [Future Improvements](#future-improvements)




<!-- ABOUT THE PROJECT -->
## About The Project

![Fakebook](https://user-images.githubusercontent.com/25479050/84653033-88519780-af04-11ea-919d-02a137ffabd0.gif)

"Fake social web" is our implementation of facebook using Ruby on Rails. It is a project developed while attending the [Microverse](http://microverse.org/) Software Development Program.The technical goals of the project were to be able to emulate some of the functionalities that Facebook has implemented, such as allowing the users to have friends in a symmetrical irreflexive way, accept & send friend requests, submit posts, and view and comment on posts created by their friends. The app is tested with RSpec and it uses PostgreSQL as the main database.

 

### Built With
* [Ruby on Rails](https://rubyonrails.org/)


### Features
- Send friend requests.
- Accept friend requests.
- Remove friends.
- Add posts.
- Add comment to posts.
- Ability to login with facebook.
- Edit setting and profile information.


<!-- GETTING STARTED -->
## Getting Started
To get started with the app, clone the repo and then install the needed gems:
```sh
$ bundle install --without production
```

Next, migrate the database:
```sh
$ rails db:migrate
```

Finally, run the app in a local server:
```sh
$ rails server
```
## Usage
Click on the Demo link below and login in with the following details as a registered user
- Email - foobar@example.com
- Password - foobar
[Demo](https://sheltered-taiga-65616.herokuapp.com/)


## Contact
* [Olga Pelts](https://github.com/pelzolga123) 
* [Tunde Oretade](https://github.com/tundeiness)


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

## Future Improvements

# [ checkbox:unchecked ] Improve UI.
# [ checkbox:unchecked ] Add chat App.


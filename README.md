## Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

### User Stories

- [x] Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [x] Allow video posts to be played in full-screen using the YouTubePlayerView.
- [x] User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] Views should be responsive for both landscape/portrait mode.
   - [x] In portrait mode, the poster image, title, and movie overview is shown.
   - [x] In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.


### App Walkthough GIF

<img src="https://github.com/prathamrana/Flixster2/blob/master/Flixster2.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />
<img src="https://github.com/prathamrana/Flixster/blob/master/Flixster1.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />

### Notes
Describe any challenges encountered while building the app.
- [x] Landscape mode is glitchy because of the andrioid emulator being used and because of Mac OS Big Sur, even with auto-rotate enabled

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Pratham Rana]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

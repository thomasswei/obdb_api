# obdb_api

responses will be in json form

Array
(
    [Title] => Star Trek
    [Year] => 2009
    [Rated] => PG-13
    [Released] => 08 May 2009
    [Runtime] => 127 min
    [Genre] => Action, Adventure, Sci-Fi
    [Director] => J.J. Abrams
    [Writer] => Roberto Orci, Alex Kurtzman, Gene Roddenberry (television series "Star Trek")
    [Actors] => Chris Pine, Zachary Quinto, Leonard Nimoy, Eric Bana
    [Plot] => The brash James T. Kirk tries to live up to his father's legacy with Mr. Spock keeping him in check as a vengeful Romulan from the future creates black holes to destroy the Federation one planet at a time.
    [Language] => English
    [Country] => USA, Germany
    [Awards] => Won 1 Oscar. Another 23 wins & 92 nominations.
    [Poster] => https://m.media-amazon.com/images/M/MV5BMjE5NDQ5OTE4Ml5BMl5BanBnXkFtZTcwOTE3NDIzMw@@._V1_SX300.jpg
    [Ratings] => Array
        (
            [0] => Array
                (
                    [Source] => Internet Movie Database
                    [Value] => 8.0/10
                )

            [1] => Array
                (
                    [Source] => Rotten Tomatoes
                    [Value] => 94%
                )

            [2] => Array
                (
                    [Source] => Metacritic
                    [Value] => 82/100
                )

        )

    [Metascore] => 82
    [imdbRating] => 8.0
    [imdbVotes] => 555,069
    [imdbID] => tt0796366
    [Type] => movie
    [DVD] => 17 Nov 2009
    [BoxOffice] => $257,704,099
    [Production] => IMAX
    [Website] => http://www.startrekmovie.com/
    [Response] => True
)

function will use apikey to return rotton tomatoes rating

$rotten = $json['Ratings']['1']['Value'];


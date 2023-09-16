<html lang="en">
<head>
    <title>American Music Home</title>
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
    <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
    <link rel="stylesheet" href="http://mltrelstad.github.io/AmericanMusic/musicTheme.css" />
    <link rel="stylesheet" href="http://mltrelstad.github.io/AmericanMusic/musicTheme.min.css" />
    <link rel="stylesheet" href="http://mltrelstad.github.io/AmericanMusic/jquery.mobile.icons.min.css" />
    <link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile.structure-1.4.5.min.css" />
</head>
<body>
 
<div data-role="page" id="home-page">
    <div data-role="header" data-theme="a" style="background-color: black;">
        <div class="logo">
            <a href="musichome.html"><img src="amMusic.webp" style="width:400px; height:175px" />
            </a><br>
        </div>
    </div>
    <div data-role="panel" id="extLinks" data-theme="b">
      <h2>External Links</h2>
      <ul data-role="listview" data-theme="b">
        <li class="menu"><a href="http://www.google.com">Google</a></li>
        <li class="menu"><a href="http://www.amazon.com">Amazon</a></li>
        <li class="menu"><a href="http://www.target.com">Target</a></li>
        <li class="menu"><a href="http://www.musiciansfriend.com">Musician's Friend</a></li>
        <li class="menu"><a href="http://www.sweetwater.com">Sweetwater Music</a></li>
        <li class="menu"><a href="https://www.nasa.gov">NASA</a></li>
      </ul>
      <p><br><br><center>Close panel by clicking outside of it, press Esc key, or by swiping.</center></p>
    </div>
    <div data-role="header">
        <ul data-role="listview" data-theme="a">
            <li><a href="#artists">Artists</a></li>
            <li><a href="#genres">Genres</a></li>
            <li><a href="#map">Music Genres Map</a></li>
            <li><a href="#favorites">Favorites</a></li>
            <li><a href="#instruments">Instruments</a></li>
            <li><a href="#aboutme">About Me</a>
            <li><a href="#mailinglist">Mailing List</a></li>
        </ul>
    </div>
    <div data-role="main" class="ui-content" sdata-theme="a">
    </div>
    <div data-role="footer" data-theme="a">
        <h1 font-style="white">Copyright &copy; M. Trelstad. 2023.</h1>
    </div>
</div>

<div id="artists" data-role="page" data-theme="a" data-add-back-btn="true">
    <div data-role="header" data-theme="a" data-add-back-btn="true">
        <h1>Artists</h1>
    </div>
    <div data-role="content" data-theme="a">
        <p>List of popular artists throughout history of American Music.<br>
          Click an artist to visit their music genre page.</p>

          <ul data-role="listview" data-theme="c" data-filter="true">
              <li><a href="#americana">Bob Dylan</a></li>
              <li><a href="#rb">Prince</a></li>
              <li><a href="#pop">Madonna</a></li>
              <li><a href="#hiphop">Tupac Shakur</a></li>
              <li><a href="#rock">Jimi Hendrix</a></li>
              <li><a href="#pop">Michael Jackson</a></li>
              <li><a href="#hiphop">Jay-Z</a></li>
              <li><a href="#jazz">Frank Sinatra</a></li>
              <li><a href="#jazz">Billie Holiday</a></li>
              <li><a href="#rock">Elvis Presley</a></li>
              <li><a href="#classical">Beethoven</a></li>
              <li><a href="#rb">Stevie Wonder</a></li>
              <li><a href="#country">George Strait</a></li>
              <li><a href="#americana">James Taylor</a></li>
              <li><a href="#rock">Nirvana</a></li>
              <li><a href="#country">Willie Nelson</a></li>
              <li><a href="#pop">Neil Diamond</a></li>
              <li><a href="#blues">B.B. King</a></li>
              <li><a href="#country">Eagles</a></li>
              <li><a href="#hiphop">Snoop Dogg</a></li>
          </ul>
      </div>
    <div data-role="footer" data-theme="a">
      <h4>Copyright &copy; M. Trelstad. 2023.</h4>
    </div>
  </div>

    <div id="genres" data-role="page" data-theme="a" data-add-back-btn="true">
        <div data-role="header" data-theme="a" data-add-back-btn="true">
            <h1>Genres</h1>
        </div>
        <div data-role="content"data-theme="a">
            <p>List of common music genres in America.</p>

              <ul data-role="listview" data-theme="c" data-filter="true">
                  <li><a href="#rock">Rock</a></li>
                  <li><a href="#pop">Pop</a></li>
                  <li><a href="#rb">R&B</a></li>
                  <li><a href="#classical">Classical</a></li>
                  <li><a href="#hiphop">Hip hop</a></li>
                  <li><a href="#country">Country</a></li>
                  <li><a href="#jazz">Jazz</a></li>
                  <li><a href="#americana">Americana</a></li>
                  <li><a href="#blues">Blues</a></li>
              </ul>
          </div>
        <div data-role="footer" data-theme="a">
          <h4>Copyright &copy; M. Trelstad. 2023.</h4>
        </div>
</div>
<div id="map" data-role="page" data-theme="b" data-add-back-btn="true">
    <div data-role="header" data-theme="b" data-add-back-btn="true">
        <h1>Music Genres Map</h1>
    </div>
        <div data-role="content" data-theme="b">
          <p>Here are 5 of the common and earlier music genres and <br>
              what genres have derived from them.</p>
          <div class="ui-grid-d" data-theme="b">
                  <div class="ui-block-a"><div class="ui-bar ui-bar-b" style="height:60px"><u>Blues</u></div></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-b" style="height:60px"><u>Country</u></div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-b" style="height:60px"><u>Rock 'n' Roll</u></div></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-b" style="height:60px"><u>Hip Hop</u></div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-b" style="height:60px"><u>Jazz</u></div></div>
                  <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:40px">Rhythm 'n' Blues</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:40px">Bluegrass</div></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:40px">Classic Rock</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:40px">Rap</div></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:40px">Bebop</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:40px">Funk</div></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:40px">Americana</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:40px">Punk Rock</div></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:40px">Afrobeat</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:40px">Fusion</div></div>
                  <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:40px">Gospel</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:40px">Honky-Tonk</div></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:40px">Grunge</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:40px">Gangsta Rap</div></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:40px">Cool Jazz</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:40px">Soul</div></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:40px">Western Swing</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:40px">Progressive Rock</div></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:40px">Electro Hop</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:40px">Jazz Funk</div></div>
                  <div class="ui-block-a"><div class="ui-bar ui-bar-a" style="height:40px">Disco</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-b"><div class="ui-bar ui-bar-a" style="height:40px">Rockabilly</div></div>
                  <div class="ui-block-c"><div class="ui-bar ui-bar-a" style="height:40px">Hard Rock</div></div>
                  <div class="ui-block-clear"></div>
                  <div class="ui-block-d"><div class="ui-bar ui-bar-a" style="height:40px">Reggaeton</div></div>
                  <div class="ui-block-e"><div class="ui-bar ui-bar-a" style="height:40px">Acid Jazz</div></div>
                  <div class="ui-block-clear"></div>
              </div>
        </div>
    <div data-role="footer" data-theme="b">
      <h4>Copyright &copy; M. Trelstad. 2023.</h4>
    </div>
  </div>
    <div id="favorites" data-role="page" data-theme="c" data-add-back-btn="true">
        <div data-role="header" data-theme="c" data-add-back-btn="true">
            <h1>Favorites</h1>
        </div>
        <div data-role="content" data-theme="c">
            <h4>Enter some your favorite music artists:</h4>
            <form id="favoriteForm">
        <input type="text" id="favoriteInput" placeholder="Enter favorite artist">
        <button type="submit">Add artist</button>
    </form>

    <div id="favoritesList">
        <h4>Favorite artist(s):</h4>
        <ul id="favorites">

        </ul>
        <div data-role="footer" data-theme="c">
          <h4>Copyright &copy; M. Trelstad. 2023.</h4>
        </div>
    </div>

</div>

<div id="instruments" data-role="page" data-theme="c" data-add-back-btn="true">
    <div data-role="header" data-theme="c" data-add-back-btn="true">
        <h1>Instruments</h1>
    </div>
    <div data-role="content" data-theme="c">
        <p>List of common instruments in American Music History.</p>

          <ul data-role="listview" data-theme="c" data-filter="true">
              <li><a href="#">Guitar</a></li>
              <li><a href="#">Bass</a></li>
              <li><a href="#">Drums</a></li>
              <li><a href="#">Piano</a></li>
              <li><a href="#">Electronic & Turntables</a></li>
              <li><a href="#">Stringed Instruments</a></li>
              <li><a href="#">Woodwind Instruments</a></li>
              <li><a href="#">Brass Instruments</a></li>
          </ul>
      </div>
    <div data-role="footer" data-theme="b">
      <h4>Copyright &copy; M. Trelstad. 2023.</h4>
    </div>
  </div>

    <div id="aboutme" data-role="page" data-theme="a" data-add-back-btn="true">
        <div data-role="header" data-theme="a" data-add-back-btn="true">
            <h1>About Me</h1>
        </div>
        <div data-role="content">
            <p>I've been surrounded with music since I was born. My grandfather had a barbershop quartet<br>
              that he shared with his siblings. My dad and his brother are still in a trio bluegrass band.<br>
              Myself, I have been in bands since my early highschool years. I've had countless performances <br>
              with many different bands that has led me to visit 39 of the 50 states and even Canada.<br><br>
              In 2008, I took my chances at auditioning at Berklee College of Music in Boston, MA. It was<br>
              an incredible experience but my odds were pretty against me as I was one of 400 to audition<br>
              that day. That was only one day out of the 15 days of auditions they do each half year. <br>
              On top of that, Berklee only admits 1,500 each half year. It's tough competition.<br><br>
            </p>

            <center>
                Site is under construction.<br>
                Please check back another time to see if I've made progress.
            </center>
          </div>
        <div data-role="footer" data-theme="a">
          <h4>Copyright &copy; M. Trelstad. 2023.</h4>
        </div>
      </div>

      <div id="mailinglist" data-role="page" data-theme="a" data-add-back-btn="true">
          <div data-role="header" data-theme="a" data-add-back-btn="true">
              <h1>Mailing List</h1>
          </div>
          <div data-role="content">
            <h4>Join a mailing list for your favorite genre:</h4>
            <form id="contactForm">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="age">Age:</label>
                <input type="number" id="age" name="age" min="0" max="120" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="country">Country:</label>
                <input type="text" id="country" name="country" required>

                <label for="favmusic">Favorite Music Genre:</label>
                <input type="text" id="favmusic" name="favmusic">
                <br>

                <input type="submit" value="Submit">
            </form>
          </div>
          <div data-role="footer" data-theme="a">
            <h4>Copyright &copy; M. Trelstad. 2023.</h4>
          </div>
        </div>

        <div id="rock" data-role="page" data-theme="a" data-add-back-btn="true">
            <div data-role="header" data-theme="a" data-add-back-btn="true">
                <h1>Rock</h1>
            </div>
            <div data-role="content">
                <h1>Rock music</h1>
                <p>Rock 'n' roll is a popular music genre that combines elements<br>
                  of rhythm and blues (R&B), jazz, and country music with the<br>
                  addition of electric instruments. Originally associated with<br>
                  youth revolt and transgression, the genre is known for energetic<br>
                  performances, catchy melodies, and often insightful lyrics.</p>

                <img src="https://www.creativefabrica.com/wp-content/uploads/2021/05/31/1622444970/Rock-n-Roll-580x386.jpg"></img>
                <center>
                    Site is under construction.<br>
                    Please check back another time to see if I've made progress.
                </center>
              </div>
            <div data-role="footer" data-theme="a">
              <h4>Copyright &copy; M. Trelstad. 2023.</h4>
            </div>
          </div>

          <div id="pop" data-role="page" data-theme="a" data-add-back-btn="true">
              <div data-role="header" data-theme="a" data-add-back-btn="true">
                  <h1>Pop</h1>
              </div>
              <div data-role="content">
                  <h1>Pop music</h1>
                  <p>Pop music is a very broad term that describes music that is<br>
                    popular in the mainstream. The term “pop” refers to all kinds<br>
                    of genres, such as rock, country, rap, etc., but it generally<br>
                    has a catchy melody and lyrics.</p>

                  <img src="https://i.pinimg.com/originals/a1/e2/db/a1e2db058dafb9a1a36d3b18965a01d7.png" style="width:400px; height:400px"></img>
                  <center>
                      Site is under construction.<br>
                      Please check back another time to see if I've made progress.
                  </center>
                </div>
              <div data-role="footer" data-theme="a">
                <h4>Copyright &copy; M. Trelstad. 2023.</h4>
              </div>
            </div>

            <div id="rb" data-role="page" data-theme="a" data-add-back-btn="true">
                <div data-role="header" data-theme="a" data-add-back-btn="true">
                    <h1>R&B Music</h1>
                </div>
                <div data-role="content">
                    <h1>R&B music</h1>
                    <p>Historically speaking, though, "rhythm and blues" as we<br>
                      understand it today most often describes a style of music<br>
                      that developed after World War II that combines elements<br>
                      of pop, gospel, blues and jazz with a strong back beat.</p>
                    <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple115/v4/4f/cc/d4/4fccd47b-9a5b-5159-63c9-0b96d99a7935/AppIcon-1x_U007emarketing-0-7-0-85-220.png/1200x630wa.png" style="width:800px; height:400px"></img>
                    <center>
                        Site is under construction.<br>
                        Please check back another time to see if I've made progress.
                    </center>
                  </div>
                <div data-role="footer" data-theme="a">
                  <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                </div>
              </div>

              <div id="classical" data-role="page" data-theme="a" data-add-back-btn="true">
                  <div data-role="header" data-theme="a" data-add-back-btn="true">
                      <h1>Classical music</h1>
                  </div>
                  <div data-role="content">
                      <h1>Classical music</h1>
                      <p>Classical music is a genre written in Europe around<br>
                        1750 to 1830 that is characterized by its elegance, balance,<br>
                        and homophonic textures. It includes several forms like<br>
                        sonatas, symphonies, and operas.</p>
                      <img src="https://images.vexels.com/media/users/3/183383/isolated/preview/a95c0839147331723f7805aec0a2f606-cello-classical-music-symbol.png"></img>

                      <center>
                          Site is under construction.<br>
                          Please check back another time to see if I've made progress.
                      </center>
                    </div>
                  <div data-role="footer" data-theme="a">
                    <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                  </div>
                </div>

                <div id="hiphop" data-role="page" data-theme="a" data-add-back-btn="true">
                    <div data-role="header" data-theme="a" data-add-back-btn="true">
                        <h1>Hip Hop</h1>
                    </div>
                    <div data-role="content">
                        <h1>Hip Hop</h1>
                        <p>Hip-hop is a genre of music most often characterized<br>
                          by a strong, rhythmic beat and a rapping vocal track.<br>
                          The genre originated in New York City in the 1970s as<br>
                          a cultural exchange among Black, Latino, and Caribbean<br>
                          youth and has grown into one of the most consumed genres<br>
                          of music in the United States.</p>
                        <img src="https://thesciencestar.org/wp-content/uploads/2022/02/hiphop2.png"></img>

                        <center>
                            Site is under construction.<br>
                            Please check back another time to see if I've made progress.
                        </center>
                      </div>
                    <div data-role="footer" data-theme="a">
                      <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                    </div>
                  </div>

                  <div id="country" data-role="page" data-theme="a" data-add-back-btn="true">
                      <div data-role="header" data-theme="a" data-add-back-btn="true">
                          <h1>Country</h1>
                      </div>
                      <div data-role="content">
                          <h1>Country music</h1>
                          <p>Country music is known for its ballads and dance<br>
                            tunes (also known as "honky-tonk music") with simple<br>
                            form, folk lyrics, and harmonies generally accompanied<br>
                            by instruments such as banjos, fiddles, harmonicas,<br>
                            and many types of guitar (including acoustic, electric,<br>
                            steel, and resonator guitars).</p>
                          <img src="https://media.istockphoto.com/id/1181446533/vector/set-of-symbols-and-mosern-lettering-on-country-music-theme-hand-drawn-doodle-illustrations.jpg?s=612x612&w=0&k=20&c=gN78YtihGYBzheXq4H9O1XOSzxeCOVc4r29d5sPLXiM=" style="width:400px; height:400px"></img>

                          <center>
                              Site is under construction.<br>
                              Please check back another time to see if I've made progress.
                          </center>
                        </div>
                      <div data-role="footer" data-theme="a">
                        <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                      </div>
                    </div>

                    <div id="jazz" data-role="page" data-theme="a" data-add-back-btn="true">
                        <div data-role="header" data-theme="a" data-add-back-btn="true">
                            <h1>Jazz</h1>
                        </div>
                        <div data-role="content">
                            <h1>Jazz music</h1>
                            <p>Jazz music is a broad style of music characterized<br>
                              by complex harmony, syncopated rhythms, and a heavy<br>
                              emphasis on improvisation. Black musicians in<br>
                              New Orleans, Louisiana developed the jazz style in<br>
                              the early twentieth century.</p>
                            <img src="https://cdn-icons-png.flaticon.com/512/4313/4313184.png"style=" width:400px; height:400px"></img>

                            <center>
                                Site is under construction.<br>
                                Please check back another time to see if I've made progress.
                            </center>
                          </div>
                        <div data-role="footer" data-theme="a">
                          <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                        </div>
                      </div>

                      <div id="americana" data-role="page" data-theme="a" data-add-back-btn="true">
                          <div data-role="header" data-theme="a" data-add-back-btn="true">
                              <h1>Americana</h1>
                          </div>
                          <div data-role="content">
                              <h1>Americana music</h1>
                              <p>Americana is a music genre that encompasses<br>
                                traditional music styles including folk, country,<br>
                                bluegrass, blues, gospel, singer-songwriter, and<br>
                                roots music. Many of these styles emerged from<br>
                                small towns and rural regions throughout the<br>
                                nineteenth and twentieth centuries.</p>
                              <img src="https://i1.sndcdn.com/artworks-t027CC6awn8QZNEO-7njQ5Q-t500x500.jpg"></img>

                              <center>
                                  Site is under construction.<br>
                                  Please check back another time to see if I've made progress.
                              </center>
                            </div>
                          <div data-role="footer" data-theme="a">
                            <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                          </div>
                        </div>

                        <div id="blues" data-role="page" data-theme="a" data-add-back-btn="true">
                            <div data-role="header" data-theme="a" data-add-back-btn="true">
                                <h1>Blues</h1>
                            </div>
                            <div data-role="content">
                                <h1>Blues</h1>
                                <p>The blues is a form of secular folk music<br>
                                  created by African Americans in the early<br>
                                  20th century, originally in the South. Although<br>
                                  instrumental accompaniment is almost universal<br>
                                  in the blues, the blues is essentially a vocal form.</p>
                                <img src="https://ih1.redbubble.net/image.657515144.1831/st,small,845x845-pad,1000x1000,f8f8f8.u14.jpg" style=" width:400px; height:400px"></img>

                                <center>
                                    Site is under construction.<br>
                                    Please check back another time to see if I've made progress.
                                </center>
                              </div>
                            <div data-role="footer" data-theme="a">
                              <h4>Copyright &copy; M. Trelstad. 2023.</h4>
                            </div>
                          </div>

  <script>
    if (localStorage) {
        document.getElementById('contactForm').addEventListener('submit', function(event) {
            event.preventDefault();
            var name = document.getElementById('name').value;
            var age = document.getElementById('age').value;
            var email = document.getElementById('email').value;
            var country = document.getElementById('country').value;
            var favmusic = document.getElementById('favmusic').value;

            var formData = {
                name: name,
                age: age,
                email: email,
                country: country,
                favmusic: favmusic
                };

            var formDataJSON = JSON.stringify(formData);
            localStorage.setItem('userFormData', formDataJSON);
            alert('Form data saved!');
            document.getElementById('contactForm').reset();
        });

        window.onload = function() {
            var formDataJSON = localStorage.getItem('userFormData');
            if (formDataJSON) {
                var formData = JSON.parse(formDataJSON);
                document.getElementById('name').value = formData.name;
                document.getElementById('age').value = formData.age;
                document.getElementById('email').value = formData.email;
                document.getElementById('country').value = formData.country;
                document.getElementById('favmusic').value = formData.favmusic;
                }
          };
      }

    document.getElementById('favoriteForm').addEventListener('submit', function(event) {
    event.preventDefault();
    var favoriteItem = document.getElementById('favoriteInput').value;

    if (favoriteItem.trim() !== '') {
        var favoritesList = document.getElementById('favorites');
        var listItem = document.createElement('li');
        listItem.textContent = favoriteItem;
        favoritesList.appendChild(listItem);

        document.getElementById('favoriteInput').value = '';
    }
});

  </script>
</body>
</html>

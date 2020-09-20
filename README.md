<h1>🚀SpaceShip & Zombies 👽</h1>
<p>This is my first python game using Pycharm IDE.</p>
<h2>🤩 Libraries Used :</h2>
<ul>
  <li> pygame </li>
  <li> random </li>
  <li> math </li>
</ul>
<h2>😉 Necessary Methods (Compulsory) Used:</h2>
<ul>
  <li> pygame.init() </li>
  <li> pygame.display.update() </li>
</ul>
<<h2>😯 Python Data Structure, Formulas & Methods Used: </h2>
<p> I used <b> List </b> python data structure and appended element in empty lists using <i>.append </i> method.
  I also used <b> Distance Formula </b> to find distance between bullets and zombie or enemy. </p> <br>
  <h2>🧐 Certain States To Be Understood: </h2>
  <ul>
  <li> Ready: </li>
  <p> When we can't see the bullet on screen. It is in state of going to be ejected from spaceship.</p>
  <li> Fire: </li>
  <p> The state in which bullet is in moving condition. </p>
  </ul>
  <h2> Classes or Methods Used for Images, Musics, Sounds, Texts & Display: </h2>
  <h3> Images </h3>
  <ul>
    <li> pygame.image.load("image name") </li>
  </ul>
  <h3> Musics & Sounds </h3>
  <ul>
    <li> from <b> pygame </b> import <b> mixer </b> </li>
    <p> mixer class help us to handle all type of activities to perform with music in game whether it can be repeating, loading or anything to do with music.</p>
    <li> mixeer.music.load ("music file")</li>
    <li> mixeer.music.play ()</li>
    <p> Use -1 only when you want to persists this music during whole game.</p>
    <li> variable = mixer.Sound("filename") & then variable.play() </li>
  </ul>
  <h3> Texts </h3>
  <ul>
  <li>pygame.font.Font("Font family file", font-size)</li>
  <li> font.render(self, text, antialias, color, background)</li>
  </ul>
  <h3> Display </h3>
  <ul>
  <li>pygame.display.set_mode((height, width))</li>
  <p> <i> Don't Forget to use inner bracket for making it tuple.😛😂 </i></p>
  <li>pygame.display.set_caption("Text")</li>
  <li>pygame.display.set_icon("Icon variable in which  icon image is loaded")</li>
  <li>screen.blit(variable name, (x,y))</li>
  <p><i> blit means to just draw !!</i></p>
  <li>screen.fill((R,G,B))</li>
  </ul>
  <h2> Use of Math & Random Libraries: </h2>
  <p> Math library was used to implement two functions i.e. <b> sqrt() & pow(a,b) </b>.<br>
  Random library was used for <b> respawning </b> of zombie in gaming terms by giving random coordinates over a certain range of coordinates.</p>
  <h2> Use of Events: </h2>
  <ul>
  <li> To get all events we used <i>pygame.event.get()</i>.</li>
  <li> for identifying event type, we used <i>event.type</i>.</li>
  <li> to know about event of key like it is released or pressed or whether it is space, left & right arrow key or any other key, we used <i> event.key</i>.</li>
  <li> For space, right arrow & left arrow key it has to match with <b> pygame.K_SPACE, pygame.K_RIGHT and pygame.K_LEFT</b>respectively.</li>
  <li> If we close window...then while loop has to be closed & game over....we used <b>pygame.QUIT</b>.</li>
  </ul>
    

<section style="display: block; background: #69bae4; padding: 10px 15px;">
  
  <h1 style="width: 100%">
    <span align="left">
      @{ Hello World }
    </span>
    <span align="left">
      <picture>
        <source 
          media="(orientation: portrait)" 
          srcset="https://www.codewars.com/users/0xe%E2%B2%967/badges/micro https://www.codewars.com/users/0xe%E2%B2%967/badges/small https://www.codewars.com/users/0xe%E2%B2%967/badges/large" 
        />
        <a align="center" href="https://www.codewars.com/users/0xe%E2%B2%967/" target="blank">
          <source srcset="https://www.codewars.com/users/0xe%E2%B2%967/badges/large" media="(orientation: landscape)" />
          <img align="right" src="https://www.codewars.com/users/0xe%E2%B2%967/badges/large" alt="Codewars" />
        </a>    
      </picture>
    </span>
  </h1>
  <blockquote>
    Genius is a fickle beast. Sometimes you have the good fortune to work with a mad genius. Other times you are doomed to work 
    with pure madness.
    There are also times when it is hard to tell the difference.
  </blockquote>
  <h3 style="font-size: 1.4rem" align="center">I talk to machines. I solve problems. I code. ♥️ <br /> </h3>
</section>

<section style="display: inline-block; width: 150px; overflow: background-image:url('https://github.com/MuneebRabaney/MuneebRabaney/blob/master/programmer.gif');">

```rust
  
 struct Human {
  name: String,
}

impl Human {
  fn new(name: String) -> Self {
    Self { name }
  }

  fn display(&self) {
    println!("Name: \n{}", self.name);
  }
}

struct Programmer {
  human: Human,
  title: String,
  stack: Vec<String>,
  languages: Vec<String>,
}

impl Programmer {
  fn new(name: String, title: String, stack: Vec<String>, languages: Vec<String>) -> Self {
    Self {
      human: Human::new(name),
      title,
      stack,
      languages,
    }
  }

  fn display(&self) {
    self.human.display();
    println!("{}", "\n");
    println!("Title: \n{}", self.title);
    println!("{}", "\n");
    println!("Stack:");
    for technology in &self.stack {
      println!("· {}", technology);
    }
    println!("{}", "\n");
    println!("Languages:");
    for language in &self.languages {
      println!("· {}", language);
    }
  }
}

fn main() {
  let programmer = Programmer::new(
    "Muneeb Rabaney".to_string(),
    "Snr. Software Engineer".to_string(),
    vec![
      "Bun".to_string(),
      "Node".to_string(),
      "React".to_string(),
      "DotNet".to_string(),
      "Laravel".to_string(),
    ],
    vec![
      "C".to_string(), 
      "C#".to_string(), 
      "SQL".to_string(),
      "PHP".to_string(),
      "Bash".to_string(),
      "TypeScript".to_string(),
    ],
  );
  programmer.display();
}

```

</section>

<section style="display: block; overflow: hidden">
  <img   
    width="440"
    alt="Coding" 
    align="right"
    src="https://github.com/MuneebRabaney/MuneebRabaney/blob/master/programmer.gif" 
  />
</section>

 <br />
<section align="left" style="border-radius: 20px">
  Connect With <a href="https://linkedin.com/in/muneeb-rabaney/">Me</a>
  <br />
  <br />
  <a href="https://za.linkedin.com/in/muneeb-rabaney" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://za.linkedin.com/in/muneeb-rabaney" height="30" width="40" />
  </a>
  <a  href="https://stackoverflow.com/users/4433536" target="blank">
    <img style="margin: 20px 0" align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/stack-overflow.svg" alt="https://stackoverflow.com/users/4433536" height="30" width="40" />
  </a>
  <a href="https://instagram.com/@iamhewhocodes" target="blank">
    <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="i.am.he.who.codes" height="30" width="40" />
  </a>
  </section>
  <br />
<section align="left" style="border-radius: 20px">
<a style="margin: 20px 0" href="https://stackexchange.com/users/5595672">
  <img src="https://stackexchange.com/users/flair/5595672.png" width="208" height="58" alt="profile for White Rabbit on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for White Rabbit on Stack Exchange, a network of free, community-driven Q&amp;A sites" />
</a>
</section>
<section align="center" className="center-inner-nodes" style="background: #444; padding: 1rem">
 <a style="text-decoration: none;" href="https://aws.amazon.com/amplify/" target="_blank" rel="noreferrer"> <img src="https://docs.amplify.aws/assets/logo-dark.svg" alt="amplify" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://cordova.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_cordova/apache_cordova-icon.svg" alt="apachecordova" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://azure.microsoft.com/en-in/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_azure/microsoft_azure-icon.svg" alt="azure" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://babeljs.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/babeljs/babeljs-icon.svg" alt="babel" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.chartjs.org" target="_blank" rel="noreferrer"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.w3schools.com/cs/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.electronjs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg" alt="electron" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.gatsbyjs.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gatsbyjs/gatsbyjs-icon.svg" alt="gatsby" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://graphql.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://gulpjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/gulp/gulp-plain.svg" alt="gulp" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://ionicframework.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Ionic_Logo.svg" alt="ionic" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.jenkins.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://laravel.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-original.svg" alt="laravel" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://materializecss.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/prplx/svg-logos/5585531d45d294869c4eaab4d7cf2e9c167710a9/svg/materialize.svg" alt="materialize" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.php.net" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://postman.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://github.com/puppeteer/puppeteer" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pptrdev/pptrdev-official.svg" alt="puppeteer" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://redux.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.sketch.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sketchapp/sketchapp-icon.svg" alt="sketch" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.sqlite.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/sqlite/sqlite-icon.svg" alt="sqlite" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://symfony.com" target="_blank" rel="noreferrer"> <img src="https://symfony.com/logos/symfony_black_03.svg" alt="symfony" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://www.vagrantup.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/vagrantup/vagrantup-icon.svg" alt="vagrant" width="40" height="40" /> </a> &nbsp;&nbsp;
 <a style="text-decoration: none;" href="https://webpack.js.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/d00d0969292a6569d45b06d3f350f463a0107b0d/icons/webpack/webpack-original-wordmark.svg" alt="webpack" width="40" height="40" /> </a> &nbsp;&nbsp;
</section>
<section>
  <br />
  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=muneebrabaney&show_icons=true&hide=html,css,scss,blade&locale=en&layout=compact&theme=tokyonight" alt="muneebrabaney" />
  <br />
  <span style="display:blockL; width: 20px; height: auto; align: center;">&nbsp;&nbsp;</span>
  <br />
</section>


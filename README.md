![Señalador](treasureChest_6464.png)
## Señalador
Save your bookmarks in the cloud securely and privately.

### The Application
This is a place where users of the Señalador application can create tickets about bugs, features or leave comments.

The Application currently consists of five parts 
   * The [Dashboard](https://senalador.es/) 
   * An [addon](https://addons.mozilla.org/en-US/firefox/addon/se%C3%B1alador/) for Firefox on Desktop
   * An [addon](https://addons.mozilla.org/en-US/android/addon/senalador_button) for Firefox on Android
   * An [extension](https://chrome.google.com/webstore/detail/senalador/ecdgboegofmghghlhgkocgdmnnajpeii) for Chrome
   * An [extension](https://addons.opera.com/en/extensions/details/senalador/) for Opera
   
The Dashboard is a web application accessible from all devices where a browser can be installed, where users can manage their bookmarks, create, add and remove tags 
and users can create bookmarks from within the Dashboard or by using on of the four browser extensions to save new bookmarks as they appear in the wild.
 
### The Name 
It means bookmark or marker in Spanish.<br />
The logo is treasure chest and it stands for privacy and only the person with the key can access what's inside.
   
### Yet another bookmark application 
Don't we already have like tons of them ?
I had been using Pocket since it was known as **Read It Later** and despite the occasional php errors that would appear here and there it was a great application
but like all things it had to evolve or dissolve and the new version was great, I loved the new look and the name and as fas as know it even comes bundled with firefox,
that is an "outstanding achievement" for a developer and it is probably the best thing that can happen to anyone after free pizza.

The thing that was a real deal-breaker for me was the sponsored bookmarks and even worse when a ribbon appeared on top of the bookmarks
I have saved in my account reading 'Best of' or 'Pick of week'. What exactly do you mean 'Best of?', I thought, best of what? What are they doing with my bookmarks?<br />
And so it began.

### The Journey
After having built several applications and websites in php and MySQL I wanted to try something new and different something that bundles all the tools,
doesn't get in your way and let you spend time building what you want instead of spending hours and hours writing boilerplate code or having to choose amongst 
half-baked frameworks, something that is fast and easy to use. So I chose [Ruby on Rails](http://rubyonrails.org/) for the Dashboard.

I found it incredible easy to use and really powerful with a minimum learning curve I was able to release the very first version of the Dashboard
in a very short amount of time.

I read a book conveniently named [The Ruby on Rails Tutorial](https://www.railstutorial.org/) I went through all three 
samples apps and then I started working on my own. I also found invaluable and incredible helpful the [Rails Guides](http://guides.rubyonrails.org/),
especially the ones about security and how to protect your application from all sorts of attacks.

I absolutely loved the gem repository, the Active Record pattern, the generators, the migration tools, the templating engine and of course 
convention over configuration and then another big weight, namely deployment, was magically lifted from my shoulders.
Rails meet Heroku! Without leaving the comfort of the command line and just by typing two commands my awesome application was deployed in the cloud.
Apache config, Virtual hosts, app servers, database migrations all those became distant memories of the past.

However later on as my application was growing I knew it was time to go for something more cost effective and
with a greater level of control without many of the restrictions of the Heroku platform so I moved it to a VPS server.
 
### The Code
The entire codebase is privately kept in another repo. However feature requests are more than welcomed.
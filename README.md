# Fu-D-Beta

  Official repository for the Beta (Xamarin) version of the Fu D. app

# Working in Fu-D

  Xamarin forms breaks down the app into a few different code bases. You will find the folders split into Fud.Android, FuD.iOS, and FuD.
All our code will be done in the FuD folder. This is the "shared" code base. Everything we do in the "shared" code base will be automatically handled by Xamarin and converted into the Native language for each platform. 

  ## Structure
  
  When working in FuD, we will be using the **MVVM** architecture. This seperates our UI from our business logic, making code easier to test and making it more organized. FuD also implements [Xamarin Forms Shell](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/shell/). What this does is it creates a "shell" that everything sits in. This "shell" is essentially, the bottom tap bar, the flyout menu, the header, and the ability to navigate between pages. Our job now is to fill said pages with actual content.
  
  The Shell is AppShell.xaml, this acts as the 'MainPage' for all intenstive purposes. From there we insert _**Views**_ which are found in the Views folder. _**Views**_ are our Content Pages, or our UI. Views will be inserted into AppShell.xaml in their respected places. Our business logic that handles actual data will be in the _**ViewModels**_ folder. These will usually just be C# classes that will relate and [_bind_](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/data-binding/) logic to elements in the UI.  
 
# Resources

  I have linked some key words to their respective Microsoft Documentation if you need help or further research. This list of videos from Microsoft known as *Xamarin.Forms 101* These will provide help in master some of the basics of Xamarin Forms:
  
  [Xamarin.Forms 101 Playlist](https://www.youtube.com/playlist?list=PLM75ZaNQS_FaEPpqVjfQdnFaSR1EWCeNZ)
  
  Specific Videos that would help with what is currently (or going to be) in use in the project are:
  
  [Xamarin.Forms 101: Data Binding](https://www.youtube.com/watch?v=pr03CYqhFr4&list=PLM75ZaNQS_FaEPpqVjfQdnFaSR1EWCeNZ&index=1)
  
  [Xamarin.Forms 101: Commands](https://www.youtube.com/watch?v=mqI6mMZTeVE&list=PLM75ZaNQS_FaEPpqVjfQdnFaSR1EWCeNZ&index=2)
  
  [Xamarin.Forms 101: Application Resources](https://www.youtube.com/watch?v=RvwMqYU-6qA&list=PLM75ZaNQS_FaEPpqVjfQdnFaSR1EWCeNZ&index=5)
  

# SqueezeboxRepo

This Repository includes two Plugins for Logitech Media Server (LMS)
=

Qobuz-30.6.6.1zip  version 30.6.6.3
-

This is my enhanced personal version of the Qobuz Plugin from Pierre Beck and Michael Herger v3.6.6.3.

A large number of extensions, improvements and bug fixes are included, see list below.

I always follow Michael Herger's improvements and incorporate them into my version with a little delay.
So that the versions don't get in each other's way, my version always has a 0 after the first version number.
If the version of the original plugin is 2.16.10, my version would then be 20.16.10. This means that all improvements from Michael are included until version 2.16.10.

The basis is the original Qobuz plugin from Pierre Beck / Michael Herger.

https://github.com/pierrepoulpe/SqueezeboxQobuz

Since my version is based on this version, I inevitably take on board any errors that might creep in with changes or enhancements.  
As a rule, however, the problems are resolved quickly and I will of course take care of it promptly.

Here are the changes and enhancements:

1.  The menu structure has been organized, expanded and made clearer.
    
2.  In the album area, all selection variants provided by Qobuz are now available and not just 4 selected variants. If Qobuz changes or expands these variants, this will immediately be displayed in the plugin.
    
3.  The menu item 'User Purchases' can be deactivated in the settings.
    
4.  I didn't like the fact that the album information appears at the end of the track list.  
    Now when you select an album, a menu appears starting with the track list as the first single-line entry followed by the album attributes.  
    You can then jump into the track list to see the individual titles or transfer the entire album to the playlist with one click.  
    This makes it easier to get an overview of all the important data on an album, including the description and the goodies.  
    The following attributes are also displayed if Qobuz provides the data:  
    Conductor, composer, a list of other artists, a list of other albums from this label is displayed under music label, the credits are displayed in a slightly modified form (both for the album and for the individual tracks), if the MusicArtistInfo plugin is installed, its album information is also displayed -Menu added.
    
5.  Better support for LMS favorites, albums, artists, tracks and playlists can now be saved as LMS favorites and also displayed and played from the LMS favorites.  
    The final touch to your LMS favorites can be achieved by also installing the history plugin 😃.
    
6.  Extension of the artist menu to include playlists and if the MusicArtistInfo plugin is installed, its ArtistInfo menu will also be added.
    
7.  Unified menu for adding and deleting Qobuz favorites.
    
8.  For years there has been no difference between PUBLICPLAYLISTS and LATESTPLAYLISTS, which is why the LATESTPLAYLISTS menu item has been removed.
    
9.  Below the Genres menu, albums are now grouped together as described in point 2.
    
10. Extended functionality of playlists, when you click on a playlist a menu now appears with all relevant information about a playlist.  
    The menu contains the track list, number of tracks, duration, genres, artists, description, release date, date of last update, similar playlists or in the case of user playlists, a list of the user's other playlists.  
    You also have the option of deleting your own Qobuz playlists or subscribing to a Qobuz playlist.  
    Some of the information is context dependent, it is only displayed when Qobuz provides the information.
    
11. Integration of the playlist 'My weekly Q', which has now been incorporated into the basic plugin.
    
12. Qobuz is a plugin with a fairly strong submenu structure and many lists. You often have the choice to switch the view between grid and list.  
    Unfortunately, there is only ever one status for each plugin. The selected setting then always applies to all levels until it is changed again.  
    Fortunately, I was able to change this unpleasant behavior together with Craig Drummond in conjunction with material.  
    The plugin now sends information to Material so that Material can remember the user setting grid or list for each logical level (albums, artists, tracks, playlists, menus).  
    I would be interested to know whether it works as smoothly for you as it has so far for me.

13. No limitations for Qobuz playlists count.
    
14. No limitations for albums, artists or tracks playlists count.

15. A genre filter for user favorites and a second for albums and playlists, the previous main genre menu is removed

16. A track-menu. You got it if you click on a track item and select the "more..." menu item.

17. New "Albums of the week" album list 

18. New "Release radar" album list

19. Remove 'My WeeklyQ' because it's no longer supported by Qobuz, you get always the same playlist since september 2025.

20. New Artist page, you get now the more powerfull informations from the current Qobuz webplayer. 

21. New Label Page and Award Page

22. New Discover Page für Labels

23. New List of all in Qobuz available awards.

24. The album view is now configurable


I've implemented numerous new features, as seen in the Qobuz apps and web player, and transferred them to the Qobuz plugin.
These include a new artist page, an awards page, a label page, a list for discovering labels, and a list of awards listed in Qobuz.
For the most part, all the data available in the Qobuz apps can now also be accessed in the Qobuz plugin.
Features like radio stations and album and track suggestions have also been implemented.

Of course, the capabilities of the Lyrion UI are somewhat limited, but Craig is working hard to improve it.

Just to preempt the inevitable question: What about DailyQ and WeeklyQ?
Currently, these features aren't available in all Qobuz apps.
I've only been able to test them on Android so far, and the implementation is rather unusual.
Essentially, the app stores the tracks played on the device in the phone's memory, and only there.
DailyQ and WeeklyQ only function when the list contains at least 10 entries.
This list is then sent to Qobuz the first time the app is used each day, and you receive your personally generated DailyQ back.
WeeklyQ works essentially the same way, except that the process only occurs on Fridays,
and the 10 tracks are presumably a cross-section of what you listened to throughout the week.
In both cases, the phone saves the generated tracklist with 30 tracks.
If you're thinking that this means a separate DailyQ or WeeklyQ is generated on every phone, you're correct—that's exactly how it works.
You don't have to like it, but that's how Qobuz has been doing it so far.
With the now-discontinued MyWeeklyQ, it was different; everything ran on the Qobuz server,
and you could retrieve the playlist at any time with a simple command. 
The app didn't have to remember anything, and you got the same result on all clients.


History-1.5.0.zip  version 1.5.0
-
2025-10-15 Some optimizations, display radio titles, search for titles or albums in Qobuz if the plugin is installed.

The second plugin creates a playback history that shows a kind of playlist with all the songs you have listened to recently.
I've always missed something like this and find it quite practical.
At the same time, the plugin corrects a few problems with the LMS favorites.
There are both per-player settings and general settings.
Here too, just try it out and you will see what has changed. The plugin is independent of other plugins.

The address of the repository as it must be entered at LMS Settings - Manage Plugins is as follows:

https://github.com/Sveninndh/SqueezeboxRepo/raw/main/SvensRepository.xml

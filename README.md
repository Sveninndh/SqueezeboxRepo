# SqueezeboxRepo

This Repository includes two Plugins for Logitech Media Server (LMS)
=

Qobuz-30.5.4.zip  version 30.5.4
-

This is my enhanced personal version of the Qobuz Plugin from Pierre Beck and Michael Herger.

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


History-1.4.5.zip  version 1.4.5
-

The second plugin creates a playback history that shows a kind of playlist with all the songs you have listened to recently.
I've always missed something like this and find it quite practical.
At the same time, the plugin corrects a few problems with the LMS favorites. Here too, just try it out and you will see what has changed. The plugin is independent of other plugins.

The address of the repository as it must be entered at LMS Settings - Manage Plugins is as follows:

https://github.com/Sveninndh/SqueezeboxRepo/raw/main/SvensRepository.xml

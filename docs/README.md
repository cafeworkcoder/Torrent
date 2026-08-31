# adb commands

Specify magnet as url or just magnet hash number to control selected torrent. 

    # adb shell "am broadcast -a com.github.axet.torrentclient.ADD_TORRENT -e url 'magnet:?xt=urn:btih:DC...09'"

    # adb shell am broadcast -a com.github.axet.torrentclient.STOP_TORRENT -e url DC...09

    # adb shell am broadcast -a com.github.axet.torrentclient.START_TORRENT -e url DC...009

    # adb shell am broadcast -a com.github.axet.torrentclient.DELETE_TORRENT -e url DCD...09

import Cocoa
import AppKit

var imgurl : NSURL = NSURL.fileURLWithPath("/users/joe/Desktop/maxresdefault.jpg")!
var error : NSError?
var workspace = NSWorkspace.sharedWorkspace()
var screen = NSScreen.mainScreen()!

var result : Bool = workspace.setDesktopImageURL(imgurl, forScreen: screen, options: nil, error: &error)

if result {
    println("Wallpaper set!")
}

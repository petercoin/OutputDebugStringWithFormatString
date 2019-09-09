# OutputDebugStringWithFormatString
A simple wrapper for OutputDebugString (a WinAPI) to support format string like printf.

This wrapper is similar to printf and has a T() macro to handle single-byte and multi-byte characters.  
It outputs the message to system debugger and you can use DebugView to see the message.  
It could also be a easier way to debug console-less program like dynamic link library.

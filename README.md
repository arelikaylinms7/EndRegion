# EndRegion
#EndRegion ;**** Directives created by AutoIt3Wrapper_GUI **** #Include &lt;GDIPlus.au3> #Include "SDL.au3" #include &lt;WindowsConstants.au3> Opt("GUIOnEventMode", 1) Global $iBlittingMethod = 1, $asBlittingMethod[4] = ["", "SDL", "GDI+", "GDI+wSDL"] HotKeySet("{SPACE}", "_Next") Local $iWidth = 800, $iHeight = 600

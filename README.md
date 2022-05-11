# tagNMLISTVIEW
$hScreenSurface = _SDL_SetVideoMode($iWidth, $iHeight, 32, $_SDL_SWSURFACE) Case $LVN_HOTTRACK Local $tInfo = DllStructCreate($tagNMLISTVIEW, $lParam) If $tInfo.Item = 5 And $tInfo.SubItem = 2 Then ToolTip("Infos displayed here...") Else

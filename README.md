powershell -WindowStyle Hidden -Command ^
$player = New-Object Media.SoundPlayer "%TEMP%\music.wav"; ^
$player.Play()

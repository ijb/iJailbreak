iJailbreak
==========
html buillding:
"
<html>
<head>
<title>iJailbreak</title>
</head>
<body>
iJailbreak by Eladk
                                                                                                                                                     
<br>
<a href="itms-services://?action=download-manifest&url=<plist-url>">Make It Ra1n!</a>
</body>
</html>
replace <plist-url> with the plist url.
plist buillding:
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
  <key>items</key>
	<array>
		<dict>
			<key>assets</key>
			<array>
				<dict>
					<key>kind</key>
					<string>software-package</string>
					<key>url</key>
					<string><cydia.ipa></string>
				</dict>
			</array>
			<key>metadata</key>
			<dict>
				<key>bundle-identifier</key>
				<string>com.saurik.cydia</string>
				<key>bundle-version</key>
				<string>1.1</string>
				<key>kind</key>
				<string>software</string>
				<key>title</key>
				<string>Cydia</string>
			</dict>
		</dict>
	</array>
</dict>
</plist>
"
replace cydia.ipa with cydia.ipa url.
iJailbreak
# cmdkey

> संग्रहीत उपयोगकर्ता_नाम और पासवर्ड बनाएं, दिखाएं और हटाएं।
> अधिक जानकारी: <https://learn.microsoft.com/windows-server/administration/windows-commands/cmdkey>।

- सभी उपयोगकर्ता क्रेडेंशियल्स की एक सूची दिखाएं:

`cmdkey /list`

- सभी उपयोगकर्ता क्रेडेंशियल्स की एक सूची दिखाएं:

`cmdkey /add:{{सर्वर_का_नाम}} /user:{{उपयोगकर्ता_नाम}}`

- किसी विशिष्ट लक्ष्य के लिए क्रेडेंशियल हटाएं:

`cmdkey /delete {{लक्ष्य_नाम}}`

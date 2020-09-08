# 28.5.3 Generating QR codes for users

> Your service users can sign in using a QR code: you generate it using {{comm}}s

A QR code is just a way of representing some text.  Often it's a URL, but it can be any string of text.
{{Lamplight}} lets you generate QR codes for profiles in your system that you can use to produce sign-in cards, or email so that people can wave their phone at the sign-in scanner.

To produce QR codes, you need to create a {{comm}} for the people who need one.  Follow the instructions in [section 10](/en/help/index/p/10) and in the content, use the merge tag `{{qr_code}}` and {{Lamplight}} will substitute the QR code image.  If you have the {{comm}}s module you can [set up a text template](/en/help/index/p/21.1.2) to save time, or [create a Word file Template](/en/help/index/p/21.1.3).  If you do this, the merge tag is ${qr_code}.

If you want a smaller QR code, use {{qr_code_sm}}, or for an extra large one use {{qr_code_lg}}.


###### publish module


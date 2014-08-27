This repository contains a copy of the GlobalStrings.lua file extracted from each localization of World of Warcraft. Each file contains all of the localized UI strings for the relevant locale.

<table>
	<thead>
		<tr><th scope="col">Locale code</th><th scope="col">Language name</th><th scope="col">English language name</th><th scope="col">Regions where available</th></tr>
	</thead>
	<tbody>
		<tr><th scope="row">deDE</th><td>Deutsch</td><td>German</td><td>Europe</td></tr>
		<tr><th scope="row">enUS</th><td>English</td><td>English</td><td>Americas, Europe</td></tr>
		<tr><th scope="row">esES</th><td>Español (España)</td><td>Spanish (Spain)</td><td>Europe</td></tr>
		<tr><th scope="row">esMX</th><td>Español (América Latina)</td><td>Spanish (Latin America)</td><td>Americas</td></tr>
		<tr><th scope="row">frFR</th><td>Français</td><td>French</td><td>Europe</td></tr>
		<tr><th scope="row">itIT</th><td>Italiano</td><td>Italian</td><td>Europe</td></tr>
		<tr><th scope="row">ptBR</th><td>Português (Brasil)</td><td>Brazilian Portuguese</td><td>America, Europe</td></tr>
		<tr><th scope="row">ruRU</th><td>Русский</td><td>Russian</td><td>Europe</td></tr>
		<tr><th scope="row">koKR</th><td>한국어</td><td>Korean</td><td>Korea</td></tr>
		<tr><th scope="row">zhCN</th><td>简体中文</td><td>Simplified Chinese</td><td>China</td></tr>
		<tr><th scope="row">zhTW</th><td>繁體中文</td><td>Traditional Chinese</td><td>Taiwan</td></tr>
	</tbody>
</table>

enGB and ptPT are not included here as they are duplicates of enUS and ptBR, respectively. Querying [GetLocale()](http://www.wowpedia.org/API_GetLocale) in a European client even returns enUS in English and ptBR in Portuguese. If either locale is ever discovered to differ from its "base" locale, as esMX differs from esES, it will be added here.
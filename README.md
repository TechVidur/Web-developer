<?xml version='1.0' encoding='utf-8' ?>

<!-- build 20243.24.1213.2326                               -->
<workbook locale='en_US' original-version='18.1' source-build='2022.4.1 (20224.23.0209.1653)' source-platform='win' version='18.1' xml:base='https://eu-west-1a.online.tableau.com' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <AnimationOnByDefault />
    <ISO8601DefaultCalendarPref />
    <MarkAnimation />
    <ObjectModelEncapsulateLegacy />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
    <SheetIdentifierTracking />
    <SortTagCleanup />
    <WindowsPersistSimpleIdentifiers />
  </document-format-change-manifest>
  <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/workbooks/DemographicsMonthly?rev=1.8' id='DemographicsMonthly' path='/t/miralexperiences/workbooks' revision='1.8' site='miralexperiences' />
  <preferences>
    <preference name='ui.encoding.shelf.height' value='24' />
    <preference name='ui.shelf.height' value='26' />
  </preferences>
  <style>
    <style-rule element='animation'>
      <format attr='animation-on' value='ao-off' />
    </style-rule>
  </style>
  <datasources>
    <datasource hasconnection='false' inline='true' name='Parameters' version='18.1'>
      <aliases enabled='yes' />
      <column caption='Country of Nationality Parameter' datatype='string' name='[Country of Nationality Parameter]' param-domain-type='list' role='measure' type='nominal' value='&quot;United Arab Emirates&quot;'>
        <calculation class='tableau' formula='&quot;United Arab Emirates&quot;' />
        <members>
          <member value='&quot; &quot;' />
          <member value='&quot;Afghanistan&quot;' />
          <member value='&quot;Aland Islands&quot;' />
          <member value='&quot;Albania&quot;' />
          <member value='&quot;Algeria&quot;' />
          <member value='&quot;American Samoa&quot;' />
          <member value='&quot;Andorra&quot;' />
          <member value='&quot;Angola&quot;' />
          <member value='&quot;Anguilla&quot;' />
          <member value='&quot;Antarctica&quot;' />
          <member value='&quot;Antigua and Barbuda&quot;' />
          <member value='&quot;Argentina&quot;' />
          <member value='&quot;Armenia&quot;' />
          <member value='&quot;Aruba&quot;' />
          <member value='&quot;Australia&quot;' />
          <member value='&quot;Austria&quot;' />
          <member value='&quot;Azerbaijan&quot;' />
          <member value='&quot;Bahamas&quot;' />
          <member value='&quot;Bahrain&quot;' />
          <member value='&quot;Bangladesh&quot;' />
          <member value='&quot;Barbados&quot;' />
          <member value='&quot;Belarus&quot;' />
          <member value='&quot;Belgium&quot;' />
          <member value='&quot;Belize&quot;' />
          <member value='&quot;Benin&quot;' />
          <member value='&quot;Bermuda&quot;' />
          <member value='&quot;Bhutan&quot;' />
          <member value='&quot;Bolivia&quot;' />
          <member value='&quot;Bonaire&quot;' />
          <member value='&quot;Bosnia and Herzegovina&quot;' />
          <member value='&quot;Botswana&quot;' />
          <member value='&quot;Bouvet Island&quot;' />
          <member value='&quot;Brazil&quot;' />
          <member value='&quot;British Indian Ocean Territory&quot;' />
          <member value='&quot;British Virgin Islands&quot;' />
          <member value='&quot;Brunei&quot;' />
          <member value='&quot;Bulgaria&quot;' />
          <member value='&quot;Burkina Faso&quot;' />
          <member value='&quot;Burma&quot;' />
          <member value='&quot;Burundi&quot;' />
          <member value='&quot;Cambodia&quot;' />
          <member value='&quot;Cameroon&quot;' />
          <member value='&quot;Canada&quot;' />
          <member value='&quot;Cape Verde&quot;' />
          <member value='&quot;Cayman Islands&quot;' />
          <member value='&quot;Central African Republic&quot;' />
          <member value='&quot;Chad&quot;' />
          <member value='&quot;Chile&quot;' />
          <member value='&quot;China&quot;' />
          <member value='&quot;Christmas Island&quot;' />
          <member value='&quot;Cocos (Keeling) Islands&quot;' />
          <member value='&quot;Colombia&quot;' />
          <member value='&quot;Comoros&quot;' />
          <member value='&quot;Congo&quot;' />
          <member value='&quot;Cook Islands&quot;' />
          <member value='&quot;Costa Rica&quot;' />
          <member value='&quot;Cote d&apos;Ivoire&quot;' />
          <member value='&quot;Croatia&quot;' />
          <member value='&quot;Cuba&quot;' />
          <member value='&quot;Curacao&quot;' />
          <member value='&quot;Cyprus&quot;' />
          <member value='&quot;Czech Republic&quot;' />
          <member value='&quot;Denmark&quot;' />
          <member value='&quot;Djibouti&quot;' />
          <member value='&quot;Dominica&quot;' />
          <member value='&quot;Dominican Republic&quot;' />
          <member value='&quot;Ecuador&quot;' />
          <member value='&quot;Egypt&quot;' />
          <member value='&quot;El Salvador&quot;' />
          <member value='&quot;Equatorial Guinea&quot;' />
          <member value='&quot;Eritrea&quot;' />
          <member value='&quot;Estonia&quot;' />
          <member value='&quot;Ethiopia&quot;' />
          <member value='&quot;Falkland Islands (Islas Malvinas)&quot;' />
          <member value='&quot;Faroe Islands&quot;' />
          <member value='&quot;Fiji&quot;' />
          <member value='&quot;Finland&quot;' />
          <member value='&quot;France&quot;' />
          <member value='&quot;France, Metropolitan&quot;' />
          <member value='&quot;French Guiana&quot;' />
          <member value='&quot;French Polynesia&quot;' />
          <member value='&quot;French Southern and Antarctic Lands&quot;' />
          <member value='&quot;Gabon&quot;' />
          <member value='&quot;Gambia, The&quot;' />
          <member value='&quot;Gaza Strip&quot;' />
          <member value='&quot;Georgia&quot;' />
          <member value='&quot;Germany&quot;' />
          <member value='&quot;Ghana&quot;' />
          <member value='&quot;Gibraltar&quot;' />
          <member value='&quot;Greece&quot;' />
          <member value='&quot;Grenada&quot;' />
          <member value='&quot;Guam&quot;' />
          <member value='&quot;Guatemala&quot;' />
          <member value='&quot;Guernsey&quot;' />
          <member value='&quot;Guinea&quot;' />
          <member value='&quot;Guyana&quot;' />
          <member value='&quot;Haiti&quot;' />
          <member value='&quot;Honduras&quot;' />
          <member value='&quot;Hong Kong&quot;' />
          <member value='&quot;Hungary&quot;' />
          <member value='&quot;Iceland&quot;' />
          <member value='&quot;India&quot;' />
          <member value='&quot;Indonesia&quot;' />
          <member value='&quot;Iran&quot;' />
          <member value='&quot;Iraq&quot;' />
          <member value='&quot;Ireland&quot;' />
          <member value='&quot;Israel&quot;' />
          <member value='&quot;Italy&quot;' />
          <member value='&quot;Jamaica&quot;' />
          <member value='&quot;Japan&quot;' />
          <member value='&quot;Jordan&quot;' />
          <member value='&quot;Kazakhstan&quot;' />
          <member value='&quot;Kenya&quot;' />
          <member value='&quot;Kiribati&quot;' />
          <member value='&quot;Korea, North&quot;' />
          <member value='&quot;Korea, South&quot;' />
          <member value='&quot;Kosovo&quot;' />
          <member value='&quot;Kuwait&quot;' />
          <member value='&quot;Kyrgyzstan&quot;' />
          <member value='&quot;Laos&quot;' />
          <member value='&quot;Latvia&quot;' />
          <member value='&quot;Lebanon&quot;' />
          <member value='&quot;Lesotho&quot;' />
          <member value='&quot;Liberia&quot;' />
          <member value='&quot;Libya&quot;' />
          <member value='&quot;Liechtenstein&quot;' />
          <member value='&quot;Lithuania&quot;' />
          <member value='&quot;Luxembourg&quot;' />
          <member value='&quot;Macau&quot;' />
          <member value='&quot;Macedonia&quot;' />
          <member value='&quot;Madagascar&quot;' />
          <member value='&quot;Malawi&quot;' />
          <member value='&quot;Malaysia&quot;' />
          <member value='&quot;Maldives&quot;' />
          <member value='&quot;Mali&quot;' />
          <member value='&quot;Malta&quot;' />
          <member value='&quot;Marshall Islands&quot;' />
          <member value='&quot;Martinique&quot;' />
          <member value='&quot;Mauritania&quot;' />
          <member value='&quot;Mauritius&quot;' />
          <member value='&quot;Mexico&quot;' />
          <member value='&quot;Micronesia&quot;' />
          <member value='&quot;Moldova&quot;' />
          <member value='&quot;Monaco&quot;' />
          <member value='&quot;Mongolia&quot;' />
          <member value='&quot;Montenegro&quot;' />
          <member value='&quot;Montserrat&quot;' />
          <member value='&quot;Morocco&quot;' />
          <member value='&quot;Mozambique&quot;' />
          <member value='&quot;Namibia&quot;' />
          <member value='&quot;Nauru&quot;' />
          <member value='&quot;Nepal&quot;' />
          <member value='&quot;Netherlands&quot;' />
          <member value='&quot;New Caledonia&quot;' />
          <member value='&quot;New Zealand&quot;' />
          <member value='&quot;Nicaragua&quot;' />
          <member value='&quot;Niger&quot;' />
          <member value='&quot;Nigeria&quot;' />
          <member value='&quot;Niue&quot;' />
          <member value='&quot;Norfolk Island&quot;' />
          <member value='&quot;Northern Mariana Islands&quot;' />
          <member value='&quot;Norway&quot;' />
          <member value='&quot;Oman&quot;' />
          <member value='&quot;Other&quot;' />
          <member value='&quot;Pakistan&quot;' />
          <member value='&quot;Palau&quot;' />
          <member value='&quot;Palestine&quot;' />
          <member value='&quot;Panama&quot;' />
          <member value='&quot;Papua New Guinea&quot;' />
          <member value='&quot;Paraguay&quot;' />
          <member value='&quot;Peru&quot;' />
          <member value='&quot;Philippines&quot;' />
          <member value='&quot;Pitcairn Islands&quot;' />
          <member value='&quot;Poland&quot;' />
          <member value='&quot;Portugal&quot;' />
          <member value='&quot;Puerto Rico&quot;' />
          <member value='&quot;Qatar&quot;' />
          <member value='&quot;Reunion&quot;' />
          <member value='&quot;Romania&quot;' />
          <member value='&quot;Russia&quot;' />
          <member value='&quot;Rwanda&quot;' />
          <member value='&quot;S. Georgia and S. Sandwich Islands&quot;' />
          <member value='&quot;Samoa&quot;' />
          <member value='&quot;San Marino&quot;' />
          <member value='&quot;Sao Tome and Principe&quot;' />
          <member value='&quot;Saudi Arabia&quot;' />
          <member value='&quot;Senegal&quot;' />
          <member value='&quot;Serbia&quot;' />
          <member value='&quot;Seychelles&quot;' />
          <member value='&quot;Sierra Leone&quot;' />
          <member value='&quot;Singapore&quot;' />
          <member value='&quot;Slovakia&quot;' />
          <member value='&quot;Slovenia&quot;' />
          <member value='&quot;Solomon Islands&quot;' />
          <member value='&quot;Somalia&quot;' />
          <member value='&quot;South Africa&quot;' />
          <member value='&quot;South Georgia and the Islands&quot;' />
          <member value='&quot;South Sudan&quot;' />
          <member value='&quot;Spain&quot;' />
          <member value='&quot;Sri Lanka&quot;' />
          <member value='&quot;Sudan&quot;' />
          <member value='&quot;Suriname&quot;' />
          <member value='&quot;Svalbard&quot;' />
          <member value='&quot;Swaziland&quot;' />
          <member value='&quot;Sweden&quot;' />
          <member value='&quot;Switzerland&quot;' />
          <member value='&quot;Syria&quot;' />
          <member value='&quot;Taiwan&quot;' />
          <member value='&quot;Tajikistan&quot;' />
          <member value='&quot;Tanzania&quot;' />
          <member value='&quot;Thailand&quot;' />
          <member value='&quot;Timor-Leste&quot;' />
          <member value='&quot;Togo&quot;' />
          <member value='&quot;Tonga&quot;' />
          <member value='&quot;Trinidad and Tobago&quot;' />
          <member value='&quot;Tunisia&quot;' />
          <member value='&quot;Turkey&quot;' />
          <member value='&quot;Turkmenistan&quot;' />
          <member value='&quot;Uganda&quot;' />
          <member value='&quot;Ukraine&quot;' />
          <member value='&quot;United Arab Emirates&quot;' />
          <member value='&quot;United Kingdom&quot;' />
          <member value='&quot;United States&quot;' />
          <member value='&quot;United States Minor Outlying Islands&quot;' />
          <member value='&quot;Uruguay&quot;' />
          <member value='&quot;Uzbekistan&quot;' />
          <member value='&quot;Vanuatu&quot;' />
          <member value='&quot;Venezuela&quot;' />
          <member value='&quot;Vietnam&quot;' />
          <member value='&quot;Virgin Islands&quot;' />
          <member value='&quot;Wallis and Futuna&quot;' />
          <member value='&quot;Yemen&quot;' />
          <member value='&quot;Zambia&quot;' />
          <member value='&quot;Zimbabwe&quot;' />
        </members>
      </column>
      <column caption='P2 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-31#'>
        <calculation class='tableau' formula='#2019-01-31#' />
      </column>
      <column caption='P2 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-01#'>
        <calculation class='tableau' formula='#2019-01-01#' />
      </column>
      <column caption='P1 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-31#'>
        <calculation class='tableau' formula='#2019-01-31#' />
      </column>
      <column caption='Top N' datatype='integer' name='[Parameter 1]' param-domain-type='any' role='measure' type='quantitative' value='20'>
        <calculation class='tableau' formula='20' />
      </column>
      <column caption='P1 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[Parameter 2]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-01#'>
        <calculation class='tableau' formula='#2019-01-01#' />
      </column>
    </datasource>
    <datasource caption='Demographics Dataset' inline='true' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' version='18.1'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/farahexperiences/datasources/DemographicsDataset?rev=1.8' id='DemographicsDataset' path='/t/farahexperiences/datasources' revision='1.8' site='miralexperiences' />
      <connection channel='https' class='sqlproxy' dataserver-permissions='true' dbname='DemographicsDataset' directory='/dataserver' port='443' saved-credentials-viewerid='1548472' server='eu-west-1a.online.tableau.com' server-oauth='' username='' workgroup-auth-mode='prompt'>
        <relation name='sqlproxy' table='[sqlproxy]' type='table' />
        <calculations>
          <calculation column='[Calculation_490892395359735808]' formula='IF  [Top 20 Country of Nationality]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
          <calculation column='[Calculation_490892395360825345]' formula='IF [Top 20 Country of Residence]&#13;&#10;THEN [COUNTRY_OF_RESIDENCE] ELSE &quot;Others&quot; END' />
          <calculation column='[Calculation_732679402495188995]' formula='date([SUBMIT_DATE])&#13;&#10;&#13;&#10;&#13;&#10;//DATE(left(str([DATE_KEY]),4)+&quot;-&quot;+mid(str([DATE_KEY]),5,2)+&quot;-&quot;+mid(str([DATE_KEY]),7,2))' />
          <calculation column='[Calculation_732679402495881220]' formula='&apos;1&apos;' />
          <calculation column='[Calculation_732679402495946757]' formula='&quot;Total&quot;' />
          <calculation column='[Calculation_732679402504523782]' formula='If &apos;Others&apos;=[Calculation_732679402504728584] then &apos;B&apos; else &apos;A&apos; END' />
          <calculation column='[Calculation_732679402504658951]' formula='if [Top 20 Country of Residence] then&#13;&#10;[COUNTRY_OF_RESIDENCE] else &quot;Others&quot;&#13;&#10;end' />
          <calculation column='[Calculation_732679402504728584]' formula='if [Top 20 Country of Nationality] then&#13;&#10;[NATIONALITY] else &quot;Others&quot;&#13;&#10;end' />
          <calculation column='[Calculation_732679402505031690]' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[Parameter 2] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy)]&#13;&#10;then [Number of Records] END' />
          <calculation column='[Calculation_732679402505338893]' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[P1 - From Date (copy) (copy)] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy) (copy) (copy)]&#13;&#10;then [Number of Records] END' />
          <calculation column='[Calculation_851180334268956681]' formula='IF  [Top 20 Country of Nationality]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
          <calculation column='[Country of Residence - GCC (except UAE)]' formula='CASE [COUNTRY_OF_RESIDENCE]&#10;  WHEN &quot;China&quot; THEN &quot;China&quot;&#10;  WHEN &quot;Bahrain&quot; THEN &quot;GCC except UAE&quot;&#10;  WHEN &quot;Kuwait&quot; THEN &quot;GCC except UAE&quot;&#10;  WHEN &quot;Oman&quot; THEN &quot;GCC except UAE&quot;&#10;  WHEN &quot;Qatar&quot; THEN &quot;GCC except UAE&quot;&#10;  WHEN &quot;Saudi Arabia&quot; THEN &quot;GCC except UAE&quot;&#10;  WHEN &quot;India&quot; THEN &quot;India&quot;&#10;  WHEN &quot;Russia&quot; THEN &quot;Russia&quot;&#10;  WHEN &quot;United Arab Emirates (UAE)&quot; THEN &quot;United Arab Emirates (UAE)&quot;&#10;  WHEN &quot;United Kingdom (UK)&quot; THEN &quot;United Kingdom (UK)&quot;&#10;  WHEN &quot;Austria&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Belgium&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Denmark&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Finland&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;France&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Germany&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Ireland&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Italy&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Netherlands&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Portugal&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Spain&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Sweden&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Switzerland&quot; THEN &quot;Western Europe&quot;&#10;  ELSE &quot;Other&quot;&#10;END' />
          <calculation column='[Facility Name (copy)_1432707698915254272]' formula='[COMPANY_NAME]' />
          <calculation column='[Nationality (group)]' formula='CASE [NATIONALITY]&#10;  WHEN &quot;Egypt&quot; THEN &quot;Egypt&quot;&#10;  WHEN &quot;India&quot; THEN &quot;India&quot;&#10;  WHEN &quot;Pakistan&quot; THEN &quot;Pakistan&quot;&#10;  WHEN &quot;Philippines&quot; THEN &quot;Philippines&quot;&#10;  WHEN &quot;United Arab Emirates (UAE)&quot; THEN &quot;United Arab Emirates (UAE)&quot;&#10;  WHEN &quot;United Kingdom (UK)&quot; THEN &quot;United Kingdom (UK)&quot;&#10;  WHEN &quot;Austria&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Belgium&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Denmark&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Finland&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;France&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Germany&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Ireland&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Italy&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Netherlands&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Portugal&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Spain&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Sweden&quot; THEN &quot;Western Europe&quot;&#10;  WHEN &quot;Switzerland&quot; THEN &quot;Western Europe&quot;&#10;  ELSE &quot;Other&quot;&#10;END' />
          <calculation column='[Nationality Sort (copy)]' formula='If &apos;Others&apos;=[Calculation_732679402504658951] then &apos;B&apos; else &apos;A&apos; END' />
          <calculation column='[Number of Records]' formula='1' />
        </calculations>
        <metadata-records>
          <metadata-record class='measure'>
            <remote-name>ATTENDANCE</remote-name>
            <remote-type>20</remote-type>
            <local-name>[ATTENDANCE]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>ATTENDANCE</remote-alias>
            <ordinal>2</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>COMPANY_NAME</remote-name>
            <remote-type>129</remote-type>
            <local-name>[COMPANY_NAME]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>COMPANY_NAME</remote-alias>
            <ordinal>1</ordinal>
            <layered>true</layered>
            <caption>Facility Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>COUNTRY_OF_RESIDENCE</remote-name>
            <remote-type>129</remote-type>
            <local-name>[COUNTRY_OF_RESIDENCE]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>COUNTRY_OF_RESIDENCE</remote-alias>
            <ordinal>7</ordinal>
            <layered>true</layered>
            <caption>Country of Residence</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_490892395359735808</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_490892395359735808]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_490892395359735808</remote-alias>
            <ordinal>20</ordinal>
            <layered>true</layered>
            <caption>Country of Nationality Group </caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;IF  [Top 20 Country of Nationality]&#13;
THEN [NATIONALITY] ELSE \&quot;Other\&quot; END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_490892395360825345</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_490892395360825345]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_490892395360825345</remote-alias>
            <ordinal>21</ordinal>
            <layered>true</layered>
            <caption>Country of Residence Group</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;IF [Top 20 Country of Residence]&#13;
THEN [COUNTRY_OF_RESIDENCE] ELSE \&quot;Others\&quot; END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402495188995</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402495188995]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402495188995</remote-alias>
            <ordinal>22</ordinal>
            <layered>true</layered>
            <caption>As of Date</caption>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='string' name='formula'>&quot;date([SUBMIT_DATE])&#13;
&#13;
&#13;
//DATE(left(str([DATE_KEY]),4)+\&quot;-\&quot;+mid(str([DATE_KEY]),5,2)+\&quot;-\&quot;+mid(str([DATE_KEY]),7,2))&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402495881220</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402495881220]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402495881220</remote-alias>
            <ordinal>23</ordinal>
            <layered>true</layered>
            <caption>Dummy</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;&apos;1&apos;&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402495946757</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402495946757]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402495946757</remote-alias>
            <ordinal>24</ordinal>
            <layered>true</layered>
            <caption>Header</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;\&quot;Total\&quot;&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402504523782</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402504523782]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402504523782</remote-alias>
            <ordinal>25</ordinal>
            <layered>true</layered>
            <caption>Nationality Sort</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;If &apos;Others&apos;=[Calculation_732679402504728584] then &apos;B&apos; else &apos;A&apos; END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402504658951</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402504658951]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402504658951</remote-alias>
            <ordinal>26</ordinal>
            <layered>true</layered>
            <caption>Top N Country</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;if [Top 20 Country of Residence] then&#13;
[COUNTRY_OF_RESIDENCE] else \&quot;Others\&quot;&#13;
end&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_732679402504728584</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402504728584]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402504728584</remote-alias>
            <ordinal>27</ordinal>
            <layered>true</layered>
            <caption>Top N Nationality</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;if [Top 20 Country of Nationality] then&#13;
[NATIONALITY] else \&quot;Others\&quot;&#13;
end&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Calculation_732679402505031690</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402505031690]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402505031690</remote-alias>
            <ordinal>28</ordinal>
            <layered>true</layered>
            <caption>P1 Records </caption>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
              <attribute datatype='string' name='formula'>&quot;<![CDATA[if [Calculation_732679402495188995]>= [Parameters].[Parameter 2] and [Calculation_732679402495188995]<= [Parameters].[P1 - From Date (copy)]
then [Number of Records] END]]>&quot;</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Calculation_732679402505338893</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_732679402505338893]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_732679402505338893</remote-alias>
            <ordinal>29</ordinal>
            <layered>true</layered>
            <caption>P2 Records</caption>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
              <attribute datatype='string' name='formula'>&quot;<![CDATA[if [Calculation_732679402495188995]>= [Parameters].[P1 - From Date (copy) (copy)] and [Calculation_732679402495188995]<= [Parameters].[P1 - From Date (copy) (copy) (copy)]
then [Number of Records] END]]>&quot;</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Calculation_851180334268956681</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_851180334268956681]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_851180334268956681</remote-alias>
            <ordinal>30</ordinal>
            <layered>true</layered>
            <caption>Country of Nationality Group</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;IF  [Top 20 Country of Nationality]&#13;
THEN [NATIONALITY] ELSE \&quot;Other\&quot; END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Country of Residence - GCC (except UAE)</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Country of Residence - GCC (except UAE)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Country of Residence - GCC (except UAE)</remote-alias>
            <ordinal>42</ordinal>
            <layered>true</layered>
            <caption>Country of Residence - Grouped</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;CASE [COUNTRY_OF_RESIDENCE]
  WHEN \&quot;China\&quot; THEN \&quot;China\&quot;
  WHEN \&quot;Bahrain\&quot; THEN \&quot;GCC except UAE\&quot;
  WHEN \&quot;Kuwait\&quot; THEN \&quot;GCC except UAE\&quot;
  WHEN \&quot;Oman\&quot; THEN \&quot;GCC except UAE\&quot;
  WHEN \&quot;Qatar\&quot; THEN \&quot;GCC except UAE\&quot;
  WHEN \&quot;Saudi Arabia\&quot; THEN \&quot;GCC except UAE\&quot;
  WHEN \&quot;India\&quot; THEN \&quot;India\&quot;
  WHEN \&quot;Russia\&quot; THEN \&quot;Russia\&quot;
  WHEN \&quot;United Arab Emirates (UAE)\&quot; THEN \&quot;United Arab Emirates (UAE)\&quot;
  WHEN \&quot;United Kingdom (UK)\&quot; THEN \&quot;United Kingdom (UK)\&quot;
  WHEN \&quot;Austria\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Belgium\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Denmark\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Finland\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;France\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Germany\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Ireland\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Italy\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Netherlands\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Portugal\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Spain\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Sweden\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Switzerland\&quot; THEN \&quot;Western Europe\&quot;
  ELSE \&quot;Other\&quot;
END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>DATE_KEY</remote-name>
            <remote-type>20</remote-type>
            <local-name>[DATE_KEY]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>DATE_KEY</remote-alias>
            <ordinal>0</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EMIRATE_NAME</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EMIRATE_NAME]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EMIRATE_NAME</remote-alias>
            <ordinal>12</ordinal>
            <layered>true</layered>
            <caption>Emirate</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Facility Name (copy)_1432707698915254272</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Facility Name (copy)_1432707698915254272]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Facility Name (copy)_1432707698915254272</remote-alias>
            <ordinal>32</ordinal>
            <layered>true</layered>
            <caption>Facility Name (copy)</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;[COMPANY_NAME]&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>GENDER</remote-name>
            <remote-type>129</remote-type>
            <local-name>[GENDER]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>GENDER</remote-alias>
            <ordinal>9</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>MODE_OF_TRANSPORT</remote-name>
            <remote-type>129</remote-type>
            <local-name>[MODE_OF_TRANSPORT]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>MODE_OF_TRANSPORT</remote-alias>
            <ordinal>10</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NATIONALITY</remote-name>
            <remote-type>129</remote-type>
            <local-name>[NATIONALITY]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>NATIONALITY</remote-alias>
            <ordinal>8</ordinal>
            <layered>true</layered>
            <caption>Nationality</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>NO_OF_GUEST</remote-name>
            <remote-type>129</remote-type>
            <local-name>[NO_OF_GUEST]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>NO_OF_GUEST</remote-alias>
            <ordinal>11</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Nationality (group)</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Nationality (group)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Nationality (group)</remote-alias>
            <ordinal>43</ordinal>
            <layered>true</layered>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;CASE [NATIONALITY]
  WHEN \&quot;Egypt\&quot; THEN \&quot;Egypt\&quot;
  WHEN \&quot;India\&quot; THEN \&quot;India\&quot;
  WHEN \&quot;Pakistan\&quot; THEN \&quot;Pakistan\&quot;
  WHEN \&quot;Philippines\&quot; THEN \&quot;Philippines\&quot;
  WHEN \&quot;United Arab Emirates (UAE)\&quot; THEN \&quot;United Arab Emirates (UAE)\&quot;
  WHEN \&quot;United Kingdom (UK)\&quot; THEN \&quot;United Kingdom (UK)\&quot;
  WHEN \&quot;Austria\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Belgium\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Denmark\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Finland\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;France\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Germany\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Ireland\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Italy\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Netherlands\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Portugal\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Spain\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Sweden\&quot; THEN \&quot;Western Europe\&quot;
  WHEN \&quot;Switzerland\&quot; THEN \&quot;Western Europe\&quot;
  ELSE \&quot;Other\&quot;
END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Nationality Sort (copy)</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Nationality Sort (copy)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Nationality Sort (copy)</remote-alias>
            <ordinal>36</ordinal>
            <layered>true</layered>
            <caption>Country Sort</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;If &apos;Others&apos;=[Calculation_732679402504658951] then &apos;B&apos; else &apos;A&apos; END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Number of Records</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Number of Records]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Number of Records</remote-alias>
            <ordinal>37</ordinal>
            <layered>true</layered>
            <caption>Number of Records</caption>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
              <attribute datatype='string' name='formula'>&quot;1&quot;</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>PARTICIPATION_STATUS</remote-name>
            <remote-type>129</remote-type>
            <local-name>[PARTICIPATION_STATUS]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>PARTICIPATION_STATUS</remote-alias>
            <ordinal>5</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>RESIDENT_TYPE</remote-name>
            <remote-type>129</remote-type>
            <local-name>[RESIDENT_TYPE]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>RESIDENT_TYPE</remote-alias>
            <ordinal>6</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>START_DATE</remote-name>
            <remote-type>135</remote-type>
            <local-name>[START_DATE]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>START_DATE</remote-alias>
            <ordinal>3</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>SUBMIT_DATE</remote-name>
            <remote-type>135</remote-type>
            <local-name>[SUBMIT_DATE]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>SUBMIT_DATE</remote-alias>
            <ordinal>4</ordinal>
            <layered>true</layered>
            <caption>Submit_Date</caption>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='boolean' name='CAP_CREATE_TEMP_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_ALWAYS_USE_LOCAL_MAPPING_TABLES'>false</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_PREFER_LOCAL_MAPPING_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_REMOTE_MAPPING_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_CASE_INSENSITIVE_CONTAINS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_IGNORE_HINT_CHECK_NOT_NULL'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SORT_BY'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUBQUERIES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUBQUERY_QUERY_CONTEXT'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUPPORTS_LODJOINS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUPPORT_ANALYTIC_FUNCTIONS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_TOP_N'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_USE_QUERY_FUSION'>true</attribute>
              <attribute datatype='boolean' name='CAP_SUPPORTS_SPLIT_FROM_LEFT'>true</attribute>
              <attribute datatype='boolean' name='CAP_SUPPORTS_SPLIT_FROM_RIGHT'>true</attribute>
              <attribute datatype='integer' name='charset'>0</attribute>
              <attribute datatype='string' name='collation'>&quot;binary&quot;</attribute>
              <attribute datatype='string' name='datasource'>&quot;<![CDATA[<?xml version='1.0' encoding='utf-8' ?>

<datasource :source-version='18.1' formatted-name='Demographics Dataset (local copy)' inline='true' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <ObjectModelEncapsulateLegacy />
    <ObjectModelExtractV2 />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
  </document-format-change-manifest>
  <repository-location derived-from='/t/farahexperiences/datasources/DemographicsDataset?rev=1.8' id='DemographicsDataset' path='/t/farahexperiences/datasources' revision='1.8' site='miralexperiences' />
  <connection channel='https' class='sqlproxy' dataserver-permissions='true' dbname='DemographicsDataset' directory='/dataserver' port='443' server='eu-west-1a.online.tableau.com'>
    <relation name='sqlproxy' table='[sqlproxy]' type='table' />
    <cols>
      <map key='[ATTENDANCE]' value='[sqlproxy].[ATTENDANCE]' />
      <map key='[COMPANY_NAME]' value='[sqlproxy].[COMPANY_NAME]' />
      <map key='[COUNTRY_OF_RESIDENCE]' value='[sqlproxy].[COUNTRY_OF_RESIDENCE]' />
      <map key='[Calculation_490892395359735808]' value='[sqlproxy].[Calculation_490892395359735808]' />
      <map key='[Calculation_490892395360825345]' value='[sqlproxy].[Calculation_490892395360825345]' />
      <map key='[Calculation_732679402495188995]' value='[sqlproxy].[Calculation_732679402495188995]' />
      <map key='[Calculation_732679402495881220]' value='[sqlproxy].[Calculation_732679402495881220]' />
      <map key='[Calculation_732679402495946757]' value='[sqlproxy].[Calculation_732679402495946757]' />
      <map key='[Calculation_732679402504523782]' value='[sqlproxy].[Calculation_732679402504523782]' />
      <map key='[Calculation_732679402504658951]' value='[sqlproxy].[Calculation_732679402504658951]' />
      <map key='[Calculation_732679402504728584]' value='[sqlproxy].[Calculation_732679402504728584]' />
      <map key='[Calculation_732679402505031690]' value='[sqlproxy].[Calculation_732679402505031690]' />
      <map key='[Calculation_732679402505338893]' value='[sqlproxy].[Calculation_732679402505338893]' />
      <map key='[Calculation_851180334268956681]' value='[sqlproxy].[Calculation_851180334268956681]' />
      <map key='[Country of Residence - GCC (except UAE)]' value='[sqlproxy].[Country of Residence - GCC (except UAE)]' />
      <map key='[DATE_KEY]' value='[sqlproxy].[DATE_KEY]' />
      <map key='[EMIRATE_NAME]' value='[sqlproxy].[EMIRATE_NAME]' />
      <map key='[Facility Name (copy)_1432707698915254272]' value='[sqlproxy].[Facility Name (copy)_1432707698915254272]' />
      <map key='[GENDER]' value='[sqlproxy].[GENDER]' />
      <map key='[MODE_OF_TRANSPORT]' value='[sqlproxy].[MODE_OF_TRANSPORT]' />
      <map key='[NATIONALITY]' value='[sqlproxy].[NATIONALITY]' />
      <map key='[NO_OF_GUEST]' value='[sqlproxy].[NO_OF_GUEST]' />
      <map key='[Nationality (group)]' value='[sqlproxy].[Nationality (group)]' />
      <map key='[Nationality Sort (copy)]' value='[sqlproxy].[Nationality Sort (copy)]' />
      <map key='[Number of Records]' value='[sqlproxy].[Number of Records]' />
      <map key='[PARTICIPATION_STATUS]' value='[sqlproxy].[PARTICIPATION_STATUS]' />
      <map key='[RESIDENT_TYPE]' value='[sqlproxy].[RESIDENT_TYPE]' />
      <map key='[START_DATE]' value='[sqlproxy].[START_DATE]' />
      <map key='[SUBMIT_DATE]' value='[sqlproxy].[SUBMIT_DATE]' />
    </cols>
  </connection>
  <aliases enabled='yes' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[ANSWER_ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[COMPANY_KEY]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <aliases>
      <alias key='\%null\%' value='CLYMB' />
    </aliases>
  </column>
  <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Year' datatype='datetime' default-type='ordinal' hidden='true' name='[CREATED_DATETIME]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
  <column aggregation='Count' caption='Country of Nationality Group ' datatype='string' default-type='nominal' name='[Calculation_490892395359735808]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='IF  [Top 20 Country of Nationality]&\#13;&\#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
  </column>
  <column aggregation='Count' caption='Country of Residence Group' datatype='string' default-type='nominal' name='[Calculation_490892395360825345]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='IF [Top 20 Country of Residence]&\#13;&\#10;THEN [COUNTRY_OF_RESIDENCE] ELSE &quot;Others&quot; END' />
  </column>
  <column aggregation='Year' caption='As of Date' datatype='date' default-type='ordinal' name='[Calculation_732679402495188995]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default'>
    <calculation class='tableau' formula='date([SUBMIT_DATE])&\#13;&\#10;&\#13;&\#10;&\#13;&\#10;//DATE(left(str([DATE_KEY]),4)+&quot;-&quot;+mid(str([DATE_KEY]),5,2)+&quot;-&quot;+mid(str([DATE_KEY]),7,2))' />
  </column>
  <column aggregation='Count' caption='Dummy' datatype='string' default-type='nominal' name='[Calculation_732679402495881220]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='&apos;1&apos;' />
  </column>
  <column aggregation='Count' caption='Header' datatype='string' default-type='nominal' name='[Calculation_732679402495946757]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='&quot;Total&quot;' />
  </column>
  <column aggregation='Count' caption='Nationality Sort' datatype='string' datatype-customized='true' default-type='nominal' name='[Calculation_732679402504523782]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='If &apos;Others&apos;=[Calculation_732679402504728584] then &apos;B&apos; else &apos;A&apos; END' />
  </column>
  <column aggregation='Count' caption='Top N Country' datatype='string' default-type='nominal' name='[Calculation_732679402504658951]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='if [Top 20 Country of Residence] then&\#13;&\#10;[COUNTRY_OF_RESIDENCE] else &quot;Others&quot;&\#13;&\#10;end' />
  </column>
  <column aggregation='Count' caption='Top N Nationality' datatype='string' datatype-customized='true' default-type='nominal' name='[Calculation_732679402504728584]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='if [Top 20 Country of Nationality] then&\#13;&\#10;[NATIONALITY] else &quot;Others&quot;&\#13;&\#10;end' />
  </column>
  <column aggregation='Sum' caption='P1 Attendance' datatype='real' default-type='quantitative' name='[Calculation_732679402504904713]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(sum([sqlproxy.1ixd65h1r02o0818ohlhq16n2uw8].[Calculation_732679402491359233]) *[Calculation_732679402505113611])/100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='Sum' caption='P1 Records ' datatype='integer' default-type='quantitative' name='[Calculation_732679402505031690]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
    <calculation class='tableau' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[Parameter 2] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy)]&\#13;&\#10;then [Number of Records] END' />
  </column>
  <column aggregation='User' caption='P1 Records \%' datatype='real' default-format='n\#,\#\#0.00&quot;\%&quot;;-\#,\#\#0.00&quot;\%&quot;' default-type='quantitative' name='[Calculation_732679402505113611]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(SUM([Calculation_732679402505031690])/TOTAL(SUM([Calculation_732679402505031690])))*100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='Sum' caption='P2 Attendance' datatype='real' default-type='quantitative' name='[Calculation_732679402505232396]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(sum([sqlproxy.1ixd65h1r02o0818ohlhq16n2uw8].[Calculation_732679402491437058])*[Calculation_732679402505416718])/100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='Sum' caption='P2 Records' datatype='integer' default-type='quantitative' name='[Calculation_732679402505338893]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
    <calculation class='tableau' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[P1 - From Date (copy) (copy)] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy) (copy) (copy)]&\#13;&\#10;then [Number of Records] END' />
  </column>
  <column aggregation='User' caption='P2 Records \%' datatype='real' default-format='n\#,\#\#0.00&quot;\%&quot;;-\#,\#\#0.00&quot;\%&quot;' default-type='quantitative' name='[Calculation_732679402505416718]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(SUM([Calculation_732679402505338893])/TOTAL(SUM([Calculation_732679402505338893])))*100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='User' caption='Records Variance \%' datatype='real' default-format='n\#,\#\#0.00&quot;\%&quot;;-\#,\#\#0.00&quot;\%&quot;' default-type='quantitative' name='[Calculation_732679402505531407]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(([Calculation_732679402505113611]-[Calculation_732679402505416718])/[Calculation_732679402505416718])*100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='Sum' caption='Attendance Variance \%' datatype='real' default-format='n\#,\#\#0.00&quot;\%&quot;;-\#,\#\#0.00&quot;\%&quot;' default-type='quantitative' name='[Calculation_732679402505596944]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
    <calculation class='tableau' formula='(([Calculation_732679402504904713]-[Calculation_732679402505232396])/[Calculation_732679402505232396])*100'>
      <table-calc ordering-type='Rows' />
    </calculation>
  </column>
  <column aggregation='Count' caption='Country of Nationality Group' datatype='string' default-type='nominal' name='[Calculation_851180334268956681]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='IF  [Top 20 Country of Nationality]&\#13;&\#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
  </column>
  <column aggregation='Count' caption='Country of Residence - Grouped' datatype='string' default-type='nominal' name='[Country of Residence - GCC (except UAE)]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='categorical-bin' column='[COUNTRY_OF_RESIDENCE]' default='&quot;Other&quot;' new-bin='true'>
      <bin default-name='true' value='&quot;China&quot;'>
        <value>&quot;China&quot;</value>
      </bin>
      <bin default-name='false' value='&quot;GCC except UAE&quot;'>
        <value>&quot;Bahrain&quot;</value>
        <value>&quot;Kuwait&quot;</value>
        <value>&quot;Oman&quot;</value>
        <value>&quot;Qatar&quot;</value>
        <value>&quot;Saudi Arabia&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;India&quot;'>
        <value>&quot;India&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;Russia&quot;'>
        <value>&quot;Russia&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;United Arab Emirates (UAE)&quot;'>
        <value>&quot;United Arab Emirates (UAE)&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;United Kingdom (UK)&quot;'>
        <value>&quot;United Kingdom (UK)&quot;</value>
      </bin>
      <bin default-name='false' value='&quot;Western Europe&quot;'>
        <value>&quot;Austria&quot;</value>
        <value>&quot;Belgium&quot;</value>
        <value>&quot;Denmark&quot;</value>
        <value>&quot;Finland&quot;</value>
        <value>&quot;France&quot;</value>
        <value>&quot;Germany&quot;</value>
        <value>&quot;Ireland&quot;</value>
        <value>&quot;Italy&quot;</value>
        <value>&quot;Netherlands&quot;</value>
        <value>&quot;Portugal&quot;</value>
        <value>&quot;Spain&quot;</value>
        <value>&quot;Sweden&quot;</value>
        <value>&quot;Switzerland&quot;</value>
      </bin>
    </calculation>
  </column>
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[DATE_KEY]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Emirate' datatype='string' default-type='nominal' name='[EMIRATE_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[FACT_KEY]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Facility Name (copy)' datatype='string' default-type='nominal' name='[Facility Name (copy)_1432707698915254272]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='[COMPANY_NAME]' />
  </column>
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[HEARD_ABOUT_BENNO]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[HEARD_ABOUT_FLYING_ACES]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[HEARD_ABOUT_TURBOTRACK]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' name='[Nationality (group)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='categorical-bin' column='[NATIONALITY]' default='&quot;Other&quot;' new-bin='true'>
      <bin default-name='true' value='&quot;Egypt&quot;'>
        <value>&quot;Egypt&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;India&quot;'>
        <value>&quot;India&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;Pakistan&quot;'>
        <value>&quot;Pakistan&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;Philippines&quot;'>
        <value>&quot;Philippines&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;United Arab Emirates (UAE)&quot;'>
        <value>&quot;United Arab Emirates (UAE)&quot;</value>
      </bin>
      <bin default-name='true' value='&quot;United Kingdom (UK)&quot;'>
        <value>&quot;United Kingdom (UK)&quot;</value>
      </bin>
      <bin default-name='false' value='&quot;Western Europe&quot;'>
        <value>&quot;Austria&quot;</value>
        <value>&quot;Belgium&quot;</value>
        <value>&quot;Denmark&quot;</value>
        <value>&quot;Finland&quot;</value>
        <value>&quot;France&quot;</value>
        <value>&quot;Germany&quot;</value>
        <value>&quot;Ireland&quot;</value>
        <value>&quot;Italy&quot;</value>
        <value>&quot;Netherlands&quot;</value>
        <value>&quot;Portugal&quot;</value>
        <value>&quot;Spain&quot;</value>
        <value>&quot;Sweden&quot;</value>
        <value>&quot;Switzerland&quot;</value>
      </bin>
    </calculation>
  </column>
  <column aggregation='Count' caption='Country Sort' datatype='string' default-type='nominal' name='[Nationality Sort (copy)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='tableau' formula='If &apos;Others&apos;=[Calculation_732679402504658951] then &apos;B&apos; else &apos;A&apos; END' />
  </column>
  <column aggregation='Sum' datatype='integer' default-type='quantitative' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
    <calculation class='tableau' formula='1' />
  </column>
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[RESUME_CODE]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[VISIT_DUE_TO_BENNO]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[VISIT_DUE_TO_FLYING_ACES]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[VISIT_DUE_TO_TURBOTRACK]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Migrated Data' datatype='table' default-type='quantitative' name='[__tableau_internal_object_id__].[Migrated Data]' pivot='key' role='measure' type='quantitative' user-datatype='table' visual-totals='Default' />
  <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
  <column-instance column='[Calculation_732679402504658951]' derivation='None' name='[none:Calculation_732679402504658951:nk]' pivot='key' type='nominal' />
  <column-instance column='[EMIRATE_NAME]' derivation='None' name='[none:EMIRATE_NAME:nk]' pivot='key' type='nominal' />
  <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
  <group caption='Action (Country of Residence Group,YEAR(Date),MONTH(Date))' name='[Action (Country of Residence Group,YEAR(Date),MONTH(Date))]' name-style='unqualified' user:auto-column='sheet_link'>
    <groupfilter function='crossjoin'>
      <groupfilter function='level-members' level='[Calculation_490892395360825345]' />
      <groupfilter function='level-members' level='[yr:SUBMIT_DATE:ok]' />
      <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' />
    </groupfilter>
  </group>
  <group caption='Action (Emirate)' name='[Action (Emirate)]' name-style='unqualified' user:auto-column='sheet_link'>
    <groupfilter function='crossjoin'>
      <groupfilter function='level-members' level='[EMIRATE_NAME]' />
    </groupfilter>
  </group>
  <group caption='Top N Nationality Set' name='[Top 20 Country of Nationality]' name-style='unqualified' user:ui-builder='filter-group'>
    <groupfilter count='[Parameters].[Parameter 1]' end='top' function='end' units='records' user:ui-marker='end' user:ui-top-by-field='true'>
      <groupfilter direction='DESC' expression='SUM([Calculation_732679402505031690])' function='order' user:ui-marker='order'>
        <groupfilter function='level-members' level='[NATIONALITY]' user:ui-enumeration='all' user:ui-marker='enumerate' />
      </groupfilter>
    </groupfilter>
  </group>
  <group caption='Top N Country Set' name='[Top 20 Country of Residence]' name-style='unqualified' user:ui-builder='filter-group'>
    <groupfilter count='[Parameters].[Parameter 1]' end='top' function='end' units='records' user:ui-marker='end' user:ui-top-by-field='true'>
      <groupfilter direction='DESC' expression='SUM([Calculation_732679402505031690])' function='order' user:ui-marker='order'>
        <groupfilter function='level-members' level='[COUNTRY_OF_RESIDENCE]' user:ui-enumeration='all' user:ui-marker='enumerate' />
      </groupfilter>
    </groupfilter>
  </group>
  <drill-paths>
    <drill-path name='Country of Residence, Country of Nationality'>
      <field>[COUNTRY_OF_RESIDENCE]</field>
    </drill-path>
  </drill-paths>
  <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='true' />
  <style>
    <style-rule element='mark'>
      <encoding attr='color' field='[:Measure Names]' type='palette'>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:10]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:12]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:14]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:16]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:18]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:19]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:20]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:21]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:23]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:24]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:26]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:27]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:29]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:3]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:31]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:33]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:35]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:37]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:39]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:4]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:41]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:42]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:43]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:45]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:47]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:49]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:51]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:7]&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Attendance (copy):qk:8]&quot;</bucket>
        </map>
        <map to='\#f28e2b'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Actul Attendance (copy):qk:3]&quot;</bucket>
        </map>
        <map to='\#f28e2b'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Estimated Actul Attendance (copy):qk:4]&quot;</bucket>
        </map>
      </encoding>
      <encoding attr='color' field='[none:EMIRATE_NAME:nk]' type='palette'>
        <map to='\#499894'>
          <bucket>&quot;10-14&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>\%many-values\%</bucket>
        </map>
        <map to='\#59a14f'>
          <bucket>&quot;Female&quot;</bucket>
        </map>
        <map to='\#59a14f'>
          <bucket>&quot;Fujairah&quot;</bucket>
        </map>
        <map to='\#76b7b2'>
          <bucket>&quot;Dubai&quot;</bucket>
        </map>
        <map to='\#79706e'>
          <bucket>&quot;8&quot;</bucket>
        </map>
        <map to='\#86bcb6'>
          <bucket>&quot;3&quot;</bucket>
        </map>
        <map to='\#8cd17d'>
          <bucket>&quot;2&quot;</bucket>
        </map>
        <map to='\#9c755f'>
          <bucket>\%null\%</bucket>
        </map>
        <map to='\#b07aa1'>
          <bucket>&quot;Sharjah&quot;</bucket>
        </map>
        <map to='\#b6992d'>
          <bucket>&quot;6&quot;</bucket>
        </map>
        <map to='\#bab0ac'>
          <bucket>&quot;Male&quot;</bucket>
        </map>
        <map to='\#d37295'>
          <bucket>&quot;1&quot;</bucket>
        </map>
        <map to='\#d4a6c8'>
          <bucket>&quot;50 or more&quot;</bucket>
        </map>
        <map to='\#e15759'>
          <bucket>&quot;Ajman&quot;</bucket>
        </map>
        <map to='\#edc948'>
          <bucket>&quot;Ras Al Khaimah&quot;</bucket>
        </map>
        <map to='\#f1ce63'>
          <bucket>&quot;5&quot;</bucket>
        </map>
        <map to='\#f28e2b'>
          <bucket>&quot;Abu Dhabi&quot;</bucket>
        </map>
        <map to='\#fabfd2'>
          <bucket>&quot;35-49&quot;</bucket>
        </map>
        <map to='\#ff9d9a'>
          <bucket>&quot;7&quot;</bucket>
        </map>
        <map to='\#ff9da7'>
          <bucket>&quot;Umm Al Quwain&quot;</bucket>
        </map>
        <map to='\#ffbe7d'>
          <bucket>&quot;4&quot;</bucket>
        </map>
      </encoding>
      <encoding attr='shape' field='[:Measure Names]' type='shape'>
        <map to='circle'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Budget Attendance Variance (copy):qk]&quot;</bucket>
        </map>
        <map to='circle'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Budgeted Attendance Variance\\\% (copy):qk]&quot;</bucket>
        </map>
        <map to='circle'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:Budgeted Revenue Variance\\\% (copy):qk]&quot;</bucket>
        </map>
        <map to='square'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:LY Attendance Variance (copy):qk]&quot;</bucket>
        </map>
        <map to='square'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:LY Attendance Variance\\\% (copy):qk]&quot;</bucket>
        </map>
        <map to='square'>
          <bucket>&quot;[Demographics Dataset (local copy)].[usr:LY Revenue Variance\\\% (copy):qk]&quot;</bucket>
        </map>
      </encoding>
      <encoding attr='color' field='[none:Calculation_732679402504658951:nk]' type='palette'>
        <map to='\#499894'>
          <bucket>&quot;Germany&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;Egypt&quot;</bucket>
        </map>
        <map to='\#4e79a7'>
          <bucket>&quot;India&quot;</bucket>
        </map>
        <map to='\#59a14f'>
          <bucket>&quot;United Arab Emirates (UAE)&quot;</bucket>
        </map>
        <map to='\#79706e'>
          <bucket>&quot;Italy&quot;</bucket>
        </map>
        <map to='\#86bcb6'>
          <bucket>&quot;Philippines&quot;</bucket>
        </map>
        <map to='\#8cd17d'>
          <bucket>&quot;Saudi Arabia&quot;</bucket>
        </map>
        <map to='\#9d7660'>
          <bucket>&quot;Mexico&quot;</bucket>
        </map>
        <map to='\#a0cbe8'>
          <bucket>&quot;Russia&quot;</bucket>
        </map>
        <map to='\#b07aa1'>
          <bucket>&quot;Ukraine&quot;</bucket>
        </map>
        <map to='\#b6992d'>
          <bucket>&quot;United Kingdom (UK)&quot;</bucket>
        </map>
        <map to='\#bab0ac'>
          <bucket>&quot;Kuwait&quot;</bucket>
        </map>
        <map to='\#d37295'>
          <bucket>&quot;France&quot;</bucket>
        </map>
        <map to='\#d4a6c8'>
          <bucket>&quot;Kazakhstan&quot;</bucket>
        </map>
        <map to='\#d7b5a6'>
          <bucket>&quot;Kyrgyzstan&quot;</bucket>
        </map>
        <map to='\#d7b5a6'>
          <bucket>&quot;Oman&quot;</bucket>
        </map>
        <map to='\#e15759'>
          <bucket>&quot;Brazil&quot;</bucket>
        </map>
        <map to='\#f1ce63'>
          <bucket>&quot;Australia&quot;</bucket>
        </map>
        <map to='\#f28e2b'>
          <bucket>&quot;China&quot;</bucket>
        </map>
        <map to='\#fabfd2'>
          <bucket>&quot;South Africa&quot;</bucket>
        </map>
        <map to='\#ff9d9a'>
          <bucket>&quot;United States (USA)&quot;</bucket>
        </map>
        <map to='\#ffbe7d'>
          <bucket>&quot;Others&quot;</bucket>
        </map>
      </encoding>
    </style-rule>
  </style>
  <semantic-values>
    <semantic-value key='[Country].[Name]' value='&quot;India&quot;' />
  </semantic-values>
  <datasource-dependencies datasource='Parameters'>
    <column caption='P2 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='\#2019-01-31\#'>
      <calculation class='tableau' formula='\#2019-01-31\#' />
    </column>
    <column caption='P2 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='\#2019-01-01\#'>
      <calculation class='tableau' formula='\#2019-01-01\#' />
    </column>
    <column caption='P1 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy)]' param-domain-type='any' role='measure' type='quantitative' value='\#2020-02-29\#'>
      <calculation class='tableau' formula='\#2020-02-29\#' />
    </column>
    <column caption='Top N' datatype='integer' name='[Parameter 1]' param-domain-type='any' role='measure' type='quantitative' value='20'>
      <calculation class='tableau' formula='20' />
    </column>
    <column caption='P1 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[Parameter 2]' param-domain-type='any' role='measure' type='quantitative' value='\#2020-02-01\#'>
      <calculation class='tableau' formula='\#2020-02-01\#' />
    </column>
  </datasource-dependencies>
  <object-graph>
    <objects>
      <object caption='Migrated Data' id='Migrated Data'>
        <properties context=''>
          <relation name='sqlproxy' table='[sqlproxy]' type='table' />
        </properties>
      </object>
    </objects>
  </object-graph>
</datasource>
]]>&quot;</attribute>
              <attribute datatype='string' name='dialect-definition'>&quot;<![CDATA[<dialect-definition>
  <primary-dialect class='hyper' version='0.0.0'>
  </primary-dialect>
</dialect-definition>
]]>&quot;</attribute>
              <attribute datatype='boolean' name='extract-active'>true</attribute>
              <attribute datatype='boolean' name='fast-get-server-time'>true</attribute>
              <attribute datatype='string' name='update-time'>&quot;7/17/2024 2:46:23 AM&quot;</attribute>
            </attributes>
          </metadata-record>
        </metadata-records>
      </connection>
      <overridable-settings>
        <date-options fiscal-year-start='january' start-of-week='sunday' />
        <default-date-format />
        <default-calendar-type>Gregorian</default-calendar-type>
      </overridable-settings>
      <aliases enabled='yes' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[ATTENDANCE]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <aliases>
          <alias key='%null%' value='CLYMB' />
        </aliases>
      </column>
      <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' layered='true' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column caption='Tourist/Residents' datatype='string' name='[Calculation_1133781257396064256]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;Residents&quot;&#13;&#10;ELSE &quot;Tourist&quot;&#13;&#10;END' />
      </column>
      <column aggregation='Count' caption='Country of Nationality Group ' datatype='string' default-type='nominal' layered='true' name='[Calculation_490892395359735808]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='IF  [Top 20 Country of Nationality]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
      </column>
      <column aggregation='Count' caption='Country of Residence Group' datatype='string' default-type='nominal' layered='true' name='[Calculation_490892395360825345]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='IF [Top 20 Country of Residence]&#13;&#10;THEN [COUNTRY_OF_RESIDENCE] ELSE &quot;Others&quot; END' />
      </column>
      <column aggregation='Year' caption='As of Date' datatype='date' default-type='ordinal' layered='true' name='[Calculation_732679402495188995]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default'>
        <calculation class='tableau' formula='date([SUBMIT_DATE])&#13;&#10;&#13;&#10;&#13;&#10;//DATE(left(str([DATE_KEY]),4)+&quot;-&quot;+mid(str([DATE_KEY]),5,2)+&quot;-&quot;+mid(str([DATE_KEY]),7,2))' />
      </column>
      <column aggregation='Count' caption='Dummy' datatype='string' default-type='nominal' layered='true' name='[Calculation_732679402495881220]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='&apos;1&apos;' />
      </column>
      <column aggregation='Count' caption='Header' datatype='string' default-type='nominal' layered='true' name='[Calculation_732679402495946757]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='&quot;Total&quot;' />
      </column>
      <column aggregation='Count' caption='Nationality Sort' datatype='string' datatype-customized='true' default-type='nominal' layered='true' name='[Calculation_732679402504523782]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='If &apos;Others&apos;=[Calculation_732679402504728584] then &apos;B&apos; else &apos;A&apos; END' />
      </column>
      <column aggregation='Count' caption='Top N Country' datatype='string' default-type='nominal' layered='true' name='[Calculation_732679402504658951]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='if [Top 20 Country of Residence] then&#13;&#10;[COUNTRY_OF_RESIDENCE] else &quot;Others&quot;&#13;&#10;end' />
      </column>
      <column aggregation='Count' caption='Top N Nationality' datatype='string' datatype-customized='true' default-type='nominal' layered='true' name='[Calculation_732679402504728584]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='if [Top 20 Country of Nationality] then&#13;&#10;[NATIONALITY] else &quot;Others&quot;&#13;&#10;end' />
      </column>
      <column aggregation='Sum' caption='P1 Attendance' datatype='real' default-type='quantitative' layered='true' name='[Calculation_732679402504904713]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(sum([sqlproxy.1ixd65h1r02o0818ohlhq16n2uw8].[Calculation_732679402491359233]) *[Calculation_732679402505113611])/100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Sum' caption='P1 Records ' datatype='integer' default-type='quantitative' layered='true' name='[Calculation_732679402505031690]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
        <calculation class='tableau' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[Parameter 2] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy)]&#13;&#10;then [Number of Records] END' />
      </column>
      <column aggregation='User' caption='P1 Records %' datatype='real' default-format='n#,##0.00&quot;%&quot;;-#,##0.00&quot;%&quot;' default-type='quantitative' layered='true' name='[Calculation_732679402505113611]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(SUM([Calculation_732679402505031690])/TOTAL(SUM([Calculation_732679402505031690])))*100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Sum' caption='P2 Attendance' datatype='real' default-type='quantitative' layered='true' name='[Calculation_732679402505232396]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(sum([sqlproxy.1ixd65h1r02o0818ohlhq16n2uw8].[Calculation_732679402491437058])*[Calculation_732679402505416718])/100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Sum' caption='P2 Records' datatype='integer' default-type='quantitative' layered='true' name='[Calculation_732679402505338893]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
        <calculation class='tableau' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[P1 - From Date (copy) (copy)] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy) (copy) (copy)]&#13;&#10;then [Number of Records] END' />
      </column>
      <column aggregation='User' caption='P2 Records %' datatype='real' default-format='n#,##0.00&quot;%&quot;;-#,##0.00&quot;%&quot;' default-type='quantitative' layered='true' name='[Calculation_732679402505416718]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(SUM([Calculation_732679402505338893])/TOTAL(SUM([Calculation_732679402505338893])))*100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='User' caption='Records Variance %' datatype='real' default-format='n#,##0.00&quot;%&quot;;-#,##0.00&quot;%&quot;' default-type='quantitative' layered='true' name='[Calculation_732679402505531407]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(([Calculation_732679402505113611]-[Calculation_732679402505416718])/[Calculation_732679402505416718])*100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Sum' caption='Attendance Variance %' datatype='real' default-format='n#,##0.00&quot;%&quot;;-#,##0.00&quot;%&quot;' default-type='quantitative' layered='true' name='[Calculation_732679402505596944]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <calculation class='tableau' formula='(([Calculation_732679402504904713]-[Calculation_732679402505232396])/[Calculation_732679402505232396])*100'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column caption='Submit Dt' datatype='date' name='[Calculation_756323266478395409]' role='dimension' type='ordinal'>
        <calculation class='tableau' formula='DATE([SUBMIT_DATE])' />
      </column>
      <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
        <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Count' caption='Country of Nationality Group' datatype='string' default-type='nominal' layered='true' name='[Calculation_851180334268956681]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='IF  [Top 20 Country of Nationality]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
      </column>
      <column caption='CoR Grouped' datatype='string' name='[China Country (copy)_548031817853374469]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
      </column>
      <column caption='Nationality Grouped' datatype='string' name='[Country Grouped (copy)_756323266502594583]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='IF [NATIONALITY]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
      </column>
      <column caption='Country of Nationality Group (New)' datatype='string' name='[Country of Nationality Group (copy)_1558808454741692424]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='IF  [Parameters].[Country of Nationality Parameter]=[NATIONALITY]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
      </column>
      <column aggregation='Count' caption='Country of Residence - Grouped' datatype='string' default-type='nominal' layered='true' name='[Country of Residence - GCC (except UAE)]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='categorical-bin' column='[COUNTRY_OF_RESIDENCE]' default='&quot;Other&quot;' new-bin='true'>
          <bin default-name='true' value='&quot;China&quot;'>
            <value>&quot;China&quot;</value>
          </bin>
          <bin default-name='false' value='&quot;GCC except UAE&quot;'>
            <value>&quot;Bahrain&quot;</value>
            <value>&quot;Kuwait&quot;</value>
            <value>&quot;Oman&quot;</value>
            <value>&quot;Qatar&quot;</value>
            <value>&quot;Saudi Arabia&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;India&quot;'>
            <value>&quot;India&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;Russia&quot;'>
            <value>&quot;Russia&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;United Arab Emirates (UAE)&quot;'>
            <value>&quot;United Arab Emirates (UAE)&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;United Kingdom (UK)&quot;'>
            <value>&quot;United Kingdom (UK)&quot;</value>
          </bin>
          <bin default-name='false' value='&quot;Western Europe&quot;'>
            <value>&quot;Austria&quot;</value>
            <value>&quot;Belgium&quot;</value>
            <value>&quot;Denmark&quot;</value>
            <value>&quot;Finland&quot;</value>
            <value>&quot;France&quot;</value>
            <value>&quot;Germany&quot;</value>
            <value>&quot;Ireland&quot;</value>
            <value>&quot;Italy&quot;</value>
            <value>&quot;Netherlands&quot;</value>
            <value>&quot;Portugal&quot;</value>
            <value>&quot;Spain&quot;</value>
            <value>&quot;Sweden&quot;</value>
            <value>&quot;Switzerland&quot;</value>
          </bin>
        </calculation>
      </column>
      <column caption='Country of Residence Group LR' datatype='string' name='[Country of Residence Group (copy)_756323266453856258]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='IF [Top 20 Country of Residence]&#13;&#10;THEN [COUNTRY_OF_RESIDENCE] ELSE &quot;Others&quot; END' />
      </column>
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[DATE_KEY]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' caption='Emirate' datatype='string' default-type='nominal' layered='true' name='[EMIRATE_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column caption='Emirate Grouped' datatype='string' name='[Emirate (copy)_756323266501898260]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='if [EMIRATE_NAME]=&quot;Abu Dhabi&quot; THEN &quot;Abu Dhabi&quot;&#13;&#10;ELSEIF [EMIRATE_NAME]=&quot;Dubai&quot; THEN &quot;Dubai&quot;&#13;&#10;else &quot;Other Emirates&quot;&#13;&#10;END' />
      </column>
      <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
        <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
          <table-calc ordering-type='Rows' />
        </calculation>
      </column>
      <column aggregation='Count' caption='Facility Name (copy)' datatype='string' default-type='nominal' layered='true' name='[Facility Name (copy)_1432707698915254272]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='[COMPANY_NAME]' />
      </column>
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[GENDER]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[MODE_OF_TRANSPORT]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' layered='true' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[NO_OF_GUEST]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Nationality (group)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='categorical-bin' column='[NATIONALITY]' default='&quot;Other&quot;' new-bin='true'>
          <bin default-name='true' value='&quot;Egypt&quot;'>
            <value>&quot;Egypt&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;India&quot;'>
            <value>&quot;India&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;Pakistan&quot;'>
            <value>&quot;Pakistan&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;Philippines&quot;'>
            <value>&quot;Philippines&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;United Arab Emirates (UAE)&quot;'>
            <value>&quot;United Arab Emirates (UAE)&quot;</value>
          </bin>
          <bin default-name='true' value='&quot;United Kingdom (UK)&quot;'>
            <value>&quot;United Kingdom (UK)&quot;</value>
          </bin>
          <bin default-name='false' value='&quot;Western Europe&quot;'>
            <value>&quot;Austria&quot;</value>
            <value>&quot;Belgium&quot;</value>
            <value>&quot;Denmark&quot;</value>
            <value>&quot;Finland&quot;</value>
            <value>&quot;France&quot;</value>
            <value>&quot;Germany&quot;</value>
            <value>&quot;Ireland&quot;</value>
            <value>&quot;Italy&quot;</value>
            <value>&quot;Netherlands&quot;</value>
            <value>&quot;Portugal&quot;</value>
            <value>&quot;Spain&quot;</value>
            <value>&quot;Sweden&quot;</value>
            <value>&quot;Switzerland&quot;</value>
          </bin>
        </calculation>
      </column>
      <column aggregation='Count' caption='Country Sort' datatype='string' default-type='nominal' layered='true' name='[Nationality Sort (copy)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='tableau' formula='If &apos;Others&apos;=[Calculation_732679402504658951] then &apos;B&apos; else &apos;A&apos; END' />
      </column>
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
        <calculation class='tableau' formula='1' />
      </column>
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[PARTICIPATION_STATUS]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[RESIDENT_TYPE]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Year' datatype='datetime' default-type='ordinal' layered='true' name='[START_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Count' caption='Migrated Data' datatype='table' default-type='quantitative' layered='true' name='[__tableau_internal_object_id__].[Migrated Data]' pivot='key' role='measure' type='quantitative' user-datatype='table' visual-totals='Default' />
      <column-instance column='[Top 20 Country of Nationality]' derivation='InOut' name='[io:Top 20 Country of Nationality:nk]' pivot='key' type='nominal' />
      <column-instance column='[Top 20 Country of Residence]' derivation='InOut' name='[io:Top 20 Country of Residence:nk]' pivot='key' type='nominal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
      <column-instance column='[COUNTRY_OF_RESIDENCE]' derivation='None' name='[none:COUNTRY_OF_RESIDENCE:nk]' pivot='key' type='nominal' />
      <column-instance column='[Calculation_1133781257396064256]' derivation='None' name='[none:Calculation_1133781257396064256:nk]' pivot='key' type='nominal' />
      <column-instance column='[Calculation_732679402504658951]' derivation='None' name='[none:Calculation_732679402504658951:nk]' pivot='key' type='nominal' />
      <column-instance column='[Calculation_851180334268956681]' derivation='None' name='[none:Calculation_851180334268956681:nk]' pivot='key' type='nominal' />
      <column-instance column='[China Country (copy)_548031817853374469]' derivation='None' name='[none:China Country (copy)_548031817853374469:nk]' pivot='key' type='nominal' />
      <column-instance column='[Country Grouped (copy)_756323266502594583]' derivation='None' name='[none:Country Grouped (copy)_756323266502594583:nk]' pivot='key' type='nominal' />
      <column-instance column='[Country of Residence Group (copy)_756323266453856258]' derivation='None' name='[none:Country of Residence Group (copy)_756323266453856258:nk]' pivot='key' type='nominal' />
      <column-instance column='[EMIRATE_NAME]' derivation='None' name='[none:EMIRATE_NAME:nk]' pivot='key' type='nominal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Quarter' name='[qr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:10]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:11]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Emirate (copy)_756323266501898260]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Emirate (copy)_756323266501898260]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:12]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:13]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Columns' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:14]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Columns' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:15]' pivot='key' type='quantitative'>
        <table-calc ordering-type='CellInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='CellInPane' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:16]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:17]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:18]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:19]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Rows' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COUNTRY_OF_RESIDENCE]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:1]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Rows' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Rows' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:20]' pivot='key' type='quantitative'>
        <table-calc ordering-type='ColumnInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='ColumnInPane' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:21]' pivot='key' type='quantitative'>
        <table-calc ordering-type='ColumnInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:22]' pivot='key' type='quantitative'>
        <table-calc ordering-type='ColumnInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:23]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:24]' pivot='key' type='quantitative'>
        <table-calc ordering-type='ColumnInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:26]' pivot='key' type='quantitative'>
        <table-calc ordering-type='ColumnInPane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:27]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:28]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:29]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:2]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:30]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Table' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Table' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:31]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:33]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:35]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:36]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Pane' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Pane' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:37]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:38]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:39]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:3]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Residence Group (copy)_756323266453856258:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Residence:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Residence Group (copy)_756323266453856258:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:40]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:41]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:42]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[qr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:43]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[qr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:44]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[qr:SUBMIT_DATE:ok]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:45]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[qr:SUBMIT_DATE:ok]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:46]' pivot='key' type='quantitative'>
        <table-calc ordering-type='PaneCol' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='PaneCol' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:47]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:49]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_1133781257396064256]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:4]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:50]' pivot='key' type='quantitative'>
        <table-calc ordering-type='TableCol' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='TableCol' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:51]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_1133781257396064256:nk]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:EMIRATE_NAME:nk]' />
        </table-calc>
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_1133781257396064256]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:53]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_1133781257396064256]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Emirate (copy)_756323266501898260]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:57]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:59]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:61]' pivot='key' type='quantitative'>
        <table-calc ordering-type='Columns' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Field'>
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
          <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' />
        </table-calc>
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:6]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_1133781257396064256]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_1133781257396064256]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:7]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COUNTRY_OF_RESIDENCE:nk]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:8]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:9]' pivot='key' type='quantitative'>
        <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[SUBMIT_DATE]' ordering-type='Field' />
        <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[SUBMIT_DATE]' ordering-type='Field' />
      </column-instance>
      <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <group caption='Action (Country of Residence Group,YEAR(Date),MONTH(Date))' layered='true' name='[Action (Country of Residence Group,YEAR(Date),MONTH(Date))]' name-style='unqualified' user:auto-column='sheet_link'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[Calculation_490892395360825345]' />
          <groupfilter function='level-members' level='[yr:SUBMIT_DATE:ok]' />
          <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' />
        </groupfilter>
      </group>
      <group caption='Action (Emirate)' layered='true' name='[Action (Emirate)]' name-style='unqualified' user:auto-column='sheet_link'>
        <groupfilter function='crossjoin'>
          <groupfilter function='level-members' level='[EMIRATE_NAME]' />
        </groupfilter>
      </group>
      <group caption='Top N Nationality Set' layered='true' name='[Top 20 Country of Nationality]' name-style='unqualified' user:ui-builder='filter-group'>
        <groupfilter count='[Parameters].[Parameter 1]' end='top' function='end' units='records' user:ui-marker='end' user:ui-top-by-field='true'>
          <groupfilter direction='DESC' expression='SUM([Calculation_732679402505031690])' function='order' user:ui-marker='order'>
            <groupfilter function='level-members' level='[NATIONALITY]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </groupfilter>
        </groupfilter>
      </group>
      <group caption='Top N Country Set' layered='true' name='[Top 20 Country of Residence]' name-style='unqualified' user:ui-builder='filter-group'>
        <groupfilter count='[Parameters].[Parameter 1]' end='top' function='end' units='records' user:ui-marker='end' user:ui-top-by-field='true'>
          <groupfilter direction='DESC' expression='SUM([Calculation_732679402505031690])' function='order' user:ui-marker='order'>
            <groupfilter function='level-members' level='[COUNTRY_OF_RESIDENCE]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </groupfilter>
        </groupfilter>
      </group>
      <drill-paths>
        <drill-path layered='true' name='Country of Residence, Country of Nationality'>
          <field>[COUNTRY_OF_RESIDENCE]</field>
        </drill-path>
      </drill-paths>
      <layout common-percentage='0.801779' dim-ordering='alphabetic' measure-ordering='alphabetic' parameter-percentage='0.198221' show-structure='true' user-set-layout-v2='true' />
      <style>
        <style-rule element='mark'>
          <encoding attr='color' field='[:Measure Names]' type='palette'>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:1]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:10]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:11]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:12]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:13]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:14]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:15]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:16]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:17]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:18]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:19]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:2]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:20]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:21]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:22]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:23]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:24]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:26]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:27]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:28]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:29]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:3]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:30]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:31]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:33]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:35]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:36]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:37]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:38]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:39]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:4]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:40]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:41]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:42]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:43]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:44]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:45]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:46]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:47]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:49]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:50]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:51]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:53]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:57]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:59]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:6]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:61]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:7]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:8]&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:9]&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Actul Attendance (copy):qk:3]&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Actul Attendance (copy):qk:4]&quot;</bucket>
            </map>
          </encoding>
          <encoding attr='color' field='[none:EMIRATE_NAME:nk]' type='palette'>
            <map to='#499894'>
              <bucket>&quot;10-14&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>%many-values%</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;Female&quot;</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;Fujairah&quot;</bucket>
            </map>
            <map to='#76b7b2'>
              <bucket>&quot;Dubai&quot;</bucket>
            </map>
            <map to='#79706e'>
              <bucket>&quot;8&quot;</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>&quot;3&quot;</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>&quot;2&quot;</bucket>
            </map>
            <map to='#9c755f'>
              <bucket>%null%</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>&quot;Sharjah&quot;</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>&quot;6&quot;</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>&quot;Male&quot;</bucket>
            </map>
            <map to='#d37295'>
              <bucket>&quot;1&quot;</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>&quot;50 or more&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;Ajman&quot;</bucket>
            </map>
            <map to='#edc948'>
              <bucket>&quot;Ras Al Khaimah&quot;</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>&quot;5&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;Abu Dhabi&quot;</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>&quot;35-49&quot;</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>&quot;7&quot;</bucket>
            </map>
            <map to='#ff9da7'>
              <bucket>&quot;Umm Al Quwain&quot;</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>&quot;4&quot;</bucket>
            </map>
          </encoding>
          <encoding attr='shape' field='[:Measure Names]' type='shape'>
            <map to='circle'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Budget Attendance Variance (copy):qk]&quot;</bucket>
            </map>
            <map to='circle'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Budgeted Attendance Variance\% (copy):qk]&quot;</bucket>
            </map>
            <map to='circle'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Budgeted Revenue Variance\% (copy):qk]&quot;</bucket>
            </map>
            <map to='square'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:LY Attendance Variance (copy):qk]&quot;</bucket>
            </map>
            <map to='square'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:LY Attendance Variance\% (copy):qk]&quot;</bucket>
            </map>
            <map to='square'>
              <bucket>&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:LY Revenue Variance\% (copy):qk]&quot;</bucket>
            </map>
          </encoding>
          <encoding attr='color' field='[none:Calculation_732679402504658951:nk]' type='palette'>
            <map to='#499894'>
              <bucket>&quot;Germany&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;Egypt&quot;</bucket>
            </map>
            <map to='#4e79a7'>
              <bucket>&quot;India&quot;</bucket>
            </map>
            <map to='#59a14f'>
              <bucket>&quot;United Arab Emirates (UAE)&quot;</bucket>
            </map>
            <map to='#79706e'>
              <bucket>&quot;Italy&quot;</bucket>
            </map>
            <map to='#86bcb6'>
              <bucket>&quot;Philippines&quot;</bucket>
            </map>
            <map to='#8cd17d'>
              <bucket>&quot;Saudi Arabia&quot;</bucket>
            </map>
            <map to='#9d7660'>
              <bucket>&quot;Mexico&quot;</bucket>
            </map>
            <map to='#a0cbe8'>
              <bucket>&quot;Russia&quot;</bucket>
            </map>
            <map to='#b07aa1'>
              <bucket>&quot;Ukraine&quot;</bucket>
            </map>
            <map to='#b6992d'>
              <bucket>&quot;United Kingdom (UK)&quot;</bucket>
            </map>
            <map to='#bab0ac'>
              <bucket>&quot;Kuwait&quot;</bucket>
            </map>
            <map to='#d37295'>
              <bucket>&quot;France&quot;</bucket>
            </map>
            <map to='#d4a6c8'>
              <bucket>&quot;Kazakhstan&quot;</bucket>
            </map>
            <map to='#d7b5a6'>
              <bucket>&quot;Kyrgyzstan&quot;</bucket>
            </map>
            <map to='#d7b5a6'>
              <bucket>&quot;Oman&quot;</bucket>
            </map>
            <map to='#e15759'>
              <bucket>&quot;Brazil&quot;</bucket>
            </map>
            <map to='#f1ce63'>
              <bucket>&quot;Australia&quot;</bucket>
            </map>
            <map to='#f28e2b'>
              <bucket>&quot;China&quot;</bucket>
            </map>
            <map to='#fabfd2'>
              <bucket>&quot;South Africa&quot;</bucket>
            </map>
            <map to='#ff9d9a'>
              <bucket>&quot;United States (USA)&quot;</bucket>
            </map>
            <map to='#ffbe7d'>
              <bucket>&quot;Others&quot;</bucket>
            </map>
          </encoding>
        </style-rule>
      </style>
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;India&quot;' />
      </semantic-values>
      <default-sorts>
        <manual-sort column='[none:COMPANY_NAME:nk]' direction='ASC'>
          <dictionary>
            <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
            <bucket>&quot;Yas Waterworld&quot;</bucket>
            <bucket>&quot;Warner Bros&quot;</bucket>
            <bucket>&quot;Qasr Experiences&quot;</bucket>
            <bucket>&quot;Clymb Entertainment&quot;</bucket>
          </dictionary>
        </manual-sort>
        <manual-sort column='[none:China Country (copy)_548031817853374469:nk]' direction='ASC'>
          <dictionary>
            <bucket>&quot;United Arab Emirates&quot;</bucket>
            <bucket>&quot;GCC&quot;</bucket>
            <bucket>&quot;China&quot;</bucket>
            <bucket>&quot;Russia&quot;</bucket>
            <bucket>&quot;United Kingdom&quot;</bucket>
            <bucket>&quot;Germany&quot;</bucket>
            <bucket>&quot;India&quot;</bucket>
            <bucket>&quot;United States&quot;</bucket>
            <bucket>&quot;France&quot;</bucket>
            <bucket>&quot;RoW&quot;</bucket>
          </dictionary>
        </manual-sort>
        <manual-sort column='[none:Country Grouped (copy)_756323266502594583:nk]' direction='ASC'>
          <dictionary>
            <bucket>&quot;United Arab Emirates&quot;</bucket>
            <bucket>&quot;GCC&quot;</bucket>
            <bucket>&quot;China&quot;</bucket>
            <bucket>&quot;Russia&quot;</bucket>
            <bucket>&quot;United Kingdom&quot;</bucket>
            <bucket>&quot;Germany&quot;</bucket>
            <bucket>&quot;India&quot;</bucket>
            <bucket>&quot;United States&quot;</bucket>
            <bucket>&quot;France&quot;</bucket>
            <bucket>&quot;RoW&quot;</bucket>
          </dictionary>
        </manual-sort>
      </default-sorts>
      <datasource-dependencies datasource='Parameters'>
        <column caption='Country of Nationality Parameter' datatype='string' name='[Country of Nationality Parameter]' param-domain-type='list' role='measure' type='nominal' value='&quot;United Arab Emirates&quot;'>
          <calculation class='tableau' formula='&quot;United Arab Emirates&quot;' />
        </column>
        <column caption='P2 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-31#'>
          <calculation class='tableau' formula='#2019-01-31#' />
        </column>
        <column caption='P2 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy) (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-01#'>
          <calculation class='tableau' formula='#2019-01-01#' />
        </column>
        <column caption='P1 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-31#'>
          <calculation class='tableau' formula='#2019-01-31#' />
        </column>
        <column caption='Top N' datatype='integer' name='[Parameter 1]' param-domain-type='any' role='measure' type='quantitative' value='20'>
          <calculation class='tableau' formula='20' />
        </column>
        <column caption='P1 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[Parameter 2]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-01#'>
          <calculation class='tableau' formula='#2019-01-01#' />
        </column>
      </datasource-dependencies>
      <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
        <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
          <desc>
            <formatted-text>
              <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
            </formatted-text>
          </desc>
        </column>
      </datasource-dependencies>
      <object-graph>
        <objects>
          <object caption='Migrated Data' id='Migrated Data'>
            <properties context=''>
              <relation name='sqlproxy' table='[sqlproxy]' type='table' />
            </properties>
          </object>
        </objects>
      </object-graph>
    </datasource>
    <datasource caption='Attendance SS' inline='true' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' version='18.1'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/datasources/AttendanceSS_15890356801600?rev=2.4' id='AttendanceSS_15890356801600' path='/t/miralexperiences/datasources' revision='1.8' site='miralexperiences' />
      <connection channel='https' class='sqlproxy' dataserver-permissions='true' dbname='AttendanceSS_15890356801600' directory='/dataserver' port='443' saved-credentials-viewerid='1548472' server='eu-west-1a.online.tableau.com' server-oauth='' username='' workgroup-auth-mode='prompt'>
        <relation name='sqlproxy' table='[sqlproxy]' type='table' />
        <calculations>
          <calculation column='[Calculation_2183682895431348224]' formula='COUNT([Ticket Id])' />
          <calculation column='[Partner Account DMG Code (OMNI) (group)]' formula='CASE [Partner Account DMG Code (OMNI)]&#10;  WHEN &quot;AGENCY&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;CORP&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;EHPF&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;GOV&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;HTL&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;INT&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;SCH&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;SHH&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;TO&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;TODMC&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;TOINT&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;WAFFER&quot; THEN &quot;B2B&quot;&#10;  WHEN &quot;YASSTH&quot; THEN &quot;B2B&quot;&#10;  ELSE &quot;Other&quot;&#10;END' />
        </calculations>
        <metadata-records>
          <metadata-record class='column'>
            <remote-name>Account AK</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Account AK]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Account AK</remote-alias>
            <ordinal>37</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Address</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Address]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Address</remote-alias>
            <ordinal>45</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent CRM Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent CRM Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent CRM Email</remote-alias>
            <ordinal>97</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent CRM ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent CRM ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent CRM ID</remote-alias>
            <ordinal>95</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent CRM Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent CRM Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent CRM Name</remote-alias>
            <ordinal>96</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent CRM Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent CRM Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent CRM Phone No.</remote-alias>
            <ordinal>98</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent OMNI Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent OMNI Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent OMNI Account Email</remote-alias>
            <ordinal>101</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent OMNI Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent OMNI Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent OMNI Account ID</remote-alias>
            <ordinal>99</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent OMNI Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent OMNI Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent OMNI Account Name</remote-alias>
            <ordinal>100</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent OMNI Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent OMNI Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent OMNI Account Phone No.</remote-alias>
            <ordinal>102</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent Oracle Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent Oracle Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent Oracle Account ID</remote-alias>
            <ordinal>111</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent TravelBox Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent TravelBox Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent TravelBox Account Email</remote-alias>
            <ordinal>105</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent TravelBox Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent TravelBox Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent TravelBox Account ID</remote-alias>
            <ordinal>103</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent TravelBox Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent TravelBox Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent TravelBox Account Name</remote-alias>
            <ordinal>104</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent TravelBox Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent TravelBox Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent TravelBox Account Phone No.</remote-alias>
            <ordinal>106</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent Yas Arena Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent Yas Arena Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent Yas Arena Account Email</remote-alias>
            <ordinal>109</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent Yas Arena Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent Yas Arena Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent Yas Arena Account ID</remote-alias>
            <ordinal>107</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent Yas Arena Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent Yas Arena Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent Yas Arena Account Name</remote-alias>
            <ordinal>108</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Agent Yas Arena Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Agent Yas Arena Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Agent Yas Arena Account Phone No.</remote-alias>
            <ordinal>110</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Annual Pass Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Annual Pass Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Annual Pass Flag</remote-alias>
            <ordinal>16</ordinal>
            <layered>true</layered>
            <caption>Annual Pass/Seasonal Pass Flag</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Attendance Date</remote-name>
            <remote-type>133</remote-type>
            <local-name>[Attendance Date]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Attendance Date</remote-alias>
            <ordinal>1</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Attendance_Count</remote-name>
            <remote-type>5</remote-type>
            <local-name>[Attendance_Count]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Attendance_Count</remote-alias>
            <ordinal>159</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Attendence Datetime</remote-name>
            <remote-type>135</remote-type>
            <local-name>[Attendence Datetime]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Attendence Datetime</remote-alias>
            <ordinal>0</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>B2B Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[B2B Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>B2B Account ID</remote-alias>
            <ordinal>64</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Media Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Base Media Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Media Code</remote-alias>
            <ordinal>124</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Media ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Base Media ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Media ID</remote-alias>
            <ordinal>123</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Sale Channel</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Base Sale Channel]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Sale Channel</remote-alias>
            <ordinal>156</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Sale ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Base Sale ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Sale ID</remote-alias>
            <ordinal>121</ordinal>
            <layered>true</layered>
            <caption>Base Sale ID/Invoice ID</caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Sale Workstation Area</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Base Sale Workstation Area]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Sale Workstation Area</remote-alias>
            <ordinal>155</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Sale Workstation ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Base Sale Workstation ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Sale Workstation ID</remote-alias>
            <ordinal>154</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Ticket Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Base Ticket Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Ticket Code</remote-alias>
            <ordinal>125</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Base Ticket ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Base Ticket ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Base Ticket ID</remote-alias>
            <ordinal>122</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Budget Attendance</remote-name>
            <remote-type>5</remote-type>
            <local-name>[Budget Attendance]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Budget Attendance</remote-alias>
            <ordinal>134</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CREATED_DATETIME</remote-name>
            <remote-type>135</remote-type>
            <local-name>[CREATED_DATETIME]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CREATED_DATETIME</remote-alias>
            <ordinal>185</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account DMG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account DMG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account DMG Code</remote-alias>
            <ordinal>69</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account DMG Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account DMG Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account DMG Name</remote-alias>
            <ordinal>70</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account Email</remote-alias>
            <ordinal>67</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account ID</remote-alias>
            <ordinal>65</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account Name</remote-alias>
            <ordinal>66</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account Phone No.</remote-alias>
            <ordinal>68</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account SubDMG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account SubDMG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account SubDMG Code</remote-alias>
            <ordinal>71</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>CRM Account SubDMG Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[CRM Account SubDMG Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>CRM Account SubDMG Name</remote-alias>
            <ordinal>72</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Calculation_2183682895431348224</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Calculation_2183682895431348224]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Calculation_2183682895431348224</remote-alias>
            <ordinal>195</ordinal>
            <hidden>true</hidden>
            <layered>true</layered>
            <caption>Attendance Count</caption>
            <local-type>integer</local-type>
            <aggregation>User</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
              <attribute datatype='string' name='formula'>&quot;COUNT([Ticket Id])&quot;</attribute>
            </attributes>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Card Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Card Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Card Type</remote-alias>
            <ordinal>168</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>City</remote-name>
            <remote-type>129</remote-type>
            <local-name>[City]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>City</remote-alias>
            <ordinal>47</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Complimentary Product Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Complimentary Product Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Complimentary Product Flag</remote-alias>
            <ordinal>22</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Country of Residence New</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Country of Residence New]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Country of Residence New</remote-alias>
            <ordinal>162</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Country of Residence </remote-name>
            <remote-type>129</remote-type>
            <local-name>[Country of Residence ]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Country of Residence </remote-alias>
            <ordinal>43</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Customer Segment</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Customer Segment]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Customer Segment</remote-alias>
            <ordinal>173</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Customer Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Customer Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Customer Type</remote-alias>
            <ordinal>42</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>DRR_Source</remote-name>
            <remote-type>129</remote-type>
            <local-name>[DRR_Source]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>DRR_Source</remote-alias>
            <ordinal>186</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Date of Birth</remote-name>
            <remote-type>133</remote-type>
            <local-name>[Date of Birth]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Date of Birth</remote-alias>
            <ordinal>50</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Department Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Department Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Department Code</remote-alias>
            <ordinal>5</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Department Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Department Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Department Name</remote-alias>
            <ordinal>6</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Booking Flow</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Booking Flow]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Booking Flow</remote-alias>
            <ordinal>138</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Booking Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[EH Booking Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Booking Id</remote-alias>
            <ordinal>137</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Channels</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Channels]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Channels</remote-alias>
            <ordinal>147</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Client Country Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Client Country Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Client Country Name</remote-alias>
            <ordinal>139</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Client Region Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Client Region Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Client Region Name</remote-alias>
            <ordinal>140</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH DMC Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH DMC Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH DMC Flag</remote-alias>
            <ordinal>94</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Segments</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Segments]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Segments</remote-alias>
            <ordinal>149</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>EH Sub Channels</remote-name>
            <remote-type>129</remote-type>
            <local-name>[EH Sub Channels]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>EH Sub Channels</remote-alias>
            <ordinal>148</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Email </remote-name>
            <remote-type>129</remote-type>
            <local-name>[Email ]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Email </remote-alias>
            <ordinal>51</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Emirate State</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Emirate State]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Emirate State</remote-alias>
            <ordinal>48</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Etihad ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Etihad ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Etihad ID</remote-alias>
            <ordinal>54</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Farah Staff Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Farah Staff Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Farah Staff Flag</remote-alias>
            <ordinal>24</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Fax Number</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Fax Number]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Fax Number</remote-alias>
            <ordinal>53</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>First Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[First Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>First Name</remote-alias>
            <ordinal>39</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Forecast Attendance</remote-name>
            <remote-type>5</remote-type>
            <local-name>[Forecast Attendance]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Forecast Attendance</remote-alias>
            <ordinal>135</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Forecast Label</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Forecast Label]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Forecast Label</remote-alias>
            <ordinal>164</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Gate Siteid</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Gate Siteid]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Gate Siteid</remote-alias>
            <ordinal>120</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Gender</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Gender]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Gender</remote-alias>
            <ordinal>55</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Guest Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Guest Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Guest Type</remote-alias>
            <ordinal>56</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Hopper Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Hopper Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Hopper Flag</remote-alias>
            <ordinal>23</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Industry</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Industry]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Industry</remote-alias>
            <ordinal>57</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Invoice ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Invoice ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Invoice ID</remote-alias>
            <ordinal>184</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Language</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Language]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Language</remote-alias>
            <ordinal>58</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Last Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Last Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Last Name</remote-alias>
            <ordinal>41</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Local/Distant</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Local/Distant]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Local/Distant</remote-alias>
            <ordinal>172</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>MDM ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[MDM ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>MDM ID</remote-alias>
            <ordinal>61</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Marital Status</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Marital Status]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Marital Status</remote-alias>
            <ordinal>59</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Market Segment Based on Segmentation Rule 1</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Market Segment Based on Segmentation Rule 1]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Market Segment Based on Segmentation Rule 1</remote-alias>
            <ordinal>126</ordinal>
            <layered>true</layered>
            <caption>Market Segment Segmentation Rule 1</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Market Segment Group 1</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Market Segment Group 1]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Market Segment Group 1</remote-alias>
            <ordinal>128</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Market Segment Group 2</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Market Segment Group 2]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Market Segment Group 2</remote-alias>
            <ordinal>129</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Market Segment Segmentation Rule 2</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Market Segment Segmentation Rule 2]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Market Segment Segmentation Rule 2</remote-alias>
            <ordinal>127</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Media Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Media Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Media Code</remote-alias>
            <ordinal>115</ordinal>
            <layered>true</layered>
            <caption>Media Code/Voucher Code</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Middle Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Middle Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Middle Name</remote-alias>
            <ordinal>40</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Miral Staff Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Miral Staff Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Miral Staff Flag</remote-alias>
            <ordinal>174</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Miral Staff ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Miral Staff ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Miral Staff ID</remote-alias>
            <ordinal>175</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Mobile Number</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Mobile Number]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Mobile Number</remote-alias>
            <ordinal>52</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Nationality New</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Nationality New]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Nationality New</remote-alias>
            <ordinal>163</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Nationality </remote-name>
            <remote-type>129</remote-type>
            <local-name>[Nationality ]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Nationality </remote-alias>
            <ordinal>44</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OG Code</remote-alias>
            <ordinal>176</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OG Promotions Group</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OG Promotions Group]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OG Promotions Group</remote-alias>
            <ordinal>180</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OG Segment</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OG Segment]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OG Segment</remote-alias>
            <ordinal>178</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OG Type Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OG Type Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OG Type Name</remote-alias>
            <ordinal>177</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OG Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OG Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OG Type</remote-alias>
            <ordinal>179</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Category DMG Recursive Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Category DMG Recursive Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Category DMG Recursive Name</remote-alias>
            <ordinal>143</ordinal>
            <layered>true</layered>
            <caption>Account Category DMG Recursive Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Category/DMG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Category/DMG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Category/DMG Code</remote-alias>
            <ordinal>77</ordinal>
            <layered>true</layered>
            <caption>Account Category/DMG Code</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Category/DMG Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Category/DMG Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Category/DMG Name</remote-alias>
            <ordinal>78</ordinal>
            <layered>true</layered>
            <caption>Account Category/DMG Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Company Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Company Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Company Name</remote-alias>
            <ordinal>142</ordinal>
            <layered>true</layered>
            <caption>Account Company Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Email</remote-alias>
            <ordinal>75</ordinal>
            <layered>true</layered>
            <caption>Account Email</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[OMNI Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account ID</remote-alias>
            <ordinal>73</ordinal>
            <layered>true</layered>
            <caption>Account ID</caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Name</remote-alias>
            <ordinal>74</ordinal>
            <layered>true</layered>
            <caption>Account Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Account Phone No.</remote-alias>
            <ordinal>76</ordinal>
            <layered>true</layered>
            <caption>Account Phone No.</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Annual Pass y/n</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Annual Pass y/n]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Annual Pass y/n</remote-alias>
            <ordinal>25</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Multipark y/n</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Multipark y/n]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Multipark y/n</remote-alias>
            <ordinal>26</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Park Combination</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Park Combination]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Park Combination</remote-alias>
            <ordinal>27</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Promotion Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Promotion Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Promotion Code</remote-alias>
            <ordinal>29</ordinal>
            <layered>true</layered>
            <caption>Promotion Code</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>OMNI Promotion Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[OMNI Promotion Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>OMNI Promotion Name</remote-alias>
            <ordinal>28</ordinal>
            <layered>true</layered>
            <caption>Promotion Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Occupation</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Occupation]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Occupation</remote-alias>
            <ordinal>60</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Oracle Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Oracle Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Oracle Account ID</remote-alias>
            <ordinal>91</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Order ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Order ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Order ID</remote-alias>
            <ordinal>182</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Order Item ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Order Item ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Order Item ID</remote-alias>
            <ordinal>183</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>P O Box</remote-name>
            <remote-type>129</remote-type>
            <local-name>[P O Box]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>P O Box</remote-alias>
            <ordinal>46</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Parent Partner CRM Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Parent Partner CRM Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Parent Partner CRM Account ID</remote-alias>
            <ordinal>92</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Parent Partner CRM Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Parent Partner CRM Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Parent Partner CRM Account Name</remote-alias>
            <ordinal>93</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Account DMG Code (OMNI) (group)</remote-name>
            <remote-type>-1</remote-type>
            <local-name>[Partner Account DMG Code (OMNI) (group)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Account DMG Code (OMNI) (group)</remote-alias>
            <ordinal>209</ordinal>
            <layered>true</layered>
            <caption>B2B Y/N</caption>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='string' name='formula'>&quot;CASE [Partner Account DMG Code (OMNI)]
  WHEN \&quot;AGENCY\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;CORP\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;EHPF\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;GOV\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;HTL\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;INT\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;SCH\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;SHH\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;TO\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;TODMC\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;TOINT\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;WAFFER\&quot; THEN \&quot;B2B\&quot;
  WHEN \&quot;YASSTH\&quot; THEN \&quot;B2B\&quot;
  ELSE \&quot;Other\&quot;
END&quot;</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Account DMG Code (OMNI)</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Partner Account DMG Code (OMNI)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Account DMG Code (OMNI)</remote-alias>
            <ordinal>152</ordinal>
            <layered>true</layered>
            <caption>Partner Account DMG Code</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Account DMG Description (OMNI)</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Partner Account DMG Description (OMNI)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Account DMG Description (OMNI)</remote-alias>
            <ordinal>153</ordinal>
            <layered>true</layered>
            <caption>Partner Account DMG Description</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Company Account Id (OMNI)</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Partner Company Account Id (OMNI)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Company Account Id (OMNI)</remote-alias>
            <ordinal>150</ordinal>
            <layered>true</layered>
            <caption>Partner Company Account Id</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Company Account Name (OMNI)</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Partner Company Account Name (OMNI)]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Company Account Name (OMNI)</remote-alias>
            <ordinal>151</ordinal>
            <layered>true</layered>
            <caption>Partner Company Account Name</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>Partner Discount Card Number</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Partner Discount Card Number]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Discount Card Number</remote-alias>
            <ordinal>165</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Discount Expiry Date</remote-name>
            <remote-type>135</remote-type>
            <local-name>[Partner Discount Expiry Date]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Discount Expiry Date</remote-alias>
            <ordinal>166</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Partner Discount Registration Channel</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Partner Discount Registration Channel]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Partner Discount Registration Channel</remote-alias>
            <ordinal>167</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Category Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Category Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Category Code</remote-alias>
            <ordinal>18</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Category Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Category Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Category Name</remote-alias>
            <ordinal>19</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Channel</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Channel]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Channel</remote-alias>
            <ordinal>170</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Code</remote-alias>
            <ordinal>7</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Group</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Group]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Group</remote-alias>
            <ordinal>169</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Name </remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Name ]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Name </remote-alias>
            <ordinal>8</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Sub Category Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Sub Category Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Sub Category Code</remote-alias>
            <ordinal>20</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Product Sub Category Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Product Sub Category Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Product Sub Category Name</remote-alias>
            <ordinal>21</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion Classification</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion Classification]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion Classification</remote-alias>
            <ordinal>31</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion DMG Description</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion DMG Description]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion DMG Description</remote-alias>
            <ordinal>33</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion DMG</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion DMG]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion DMG</remote-alias>
            <ordinal>32</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion Flag</remote-alias>
            <ordinal>34</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion ID</remote-alias>
            <ordinal>141</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Promotion Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion Type</remote-alias>
            <ordinal>30</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion Valid From</remote-name>
            <remote-type>135</remote-type>
            <local-name>[Promotion Valid From]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion Valid From</remote-alias>
            <ordinal>35</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Promotion Valid To</remote-name>
            <remote-type>135</remote-type>
            <local-name>[Promotion Valid To]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Promotion Valid To</remote-alias>
            <ordinal>36</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>datetime</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Redemption Company Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Redemption Company Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Redemption Company Name</remote-alias>
            <ordinal>4</ordinal>
            <layered>true</layered>
            <caption>Ticket Use Facility</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Reservation Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Reservation Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Reservation Id</remote-alias>
            <ordinal>116</ordinal>
            <layered>true</layered>
            <caption>Reservation Id/Invoice No. </caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>SCV ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[SCV ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>SCV ID</remote-alias>
            <ordinal>62</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Company Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Sale Company Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Company Name</remote-alias>
            <ordinal>3</ordinal>
            <layered>true</layered>
            <caption>Ticket Sale Facility</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Sale Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Id</remote-alias>
            <ordinal>112</ordinal>
            <layered>true</layered>
            <caption>Sale ID/Invoice ID</caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Item Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Sale Item Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Item Id</remote-alias>
            <ordinal>113</ordinal>
            <layered>true</layered>
            <caption>Sale Item ID/Invoice Item ID</caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Transaction Datet</remote-name>
            <remote-type>133</remote-type>
            <local-name>[Sale Transaction Datet]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Transaction Datet</remote-alias>
            <ordinal>2</ordinal>
            <layered>true</layered>
            <caption>Sale Transaction Date</caption>
            <family>Custom SQL Query</family>
            <local-type>date</local-type>
            <aggregation>Year</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Transaction Type Desc</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Sale Transaction Type Desc]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Transaction Type Desc</remote-alias>
            <ordinal>161</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Sale Transaction Type</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Sale Transaction Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Sale Transaction Type</remote-alias>
            <ordinal>160</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Scan Action</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Scan Action]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Scan Action</remote-alias>
            <ordinal>117</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Source Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Source Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Source Name</remote-alias>
            <ordinal>136</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Age</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Age]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Age</remote-alias>
            <ordinal>11</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Code</remote-alias>
            <ordinal>9</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Description</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Description]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Description</remote-alias>
            <ordinal>10</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Ticket Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Id</remote-alias>
            <ordinal>114</ordinal>
            <layered>true</layered>
            <caption>Ticket ID/Voucher ID</caption>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Market</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Market]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Market</remote-alias>
            <ordinal>13</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Tier</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Tier]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Tier</remote-alias>
            <ordinal>12</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket Type</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket Type</remote-alias>
            <ordinal>14</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Ticket or Product Flag</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Ticket or Product Flag]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Ticket or Product Flag</remote-alias>
            <ordinal>15</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Title</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Title]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Title</remote-alias>
            <ordinal>38</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Transaction ID</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Transaction ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Transaction ID</remote-alias>
            <ordinal>171</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account Category/DMG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account Category/DMG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account Category/DMG Code</remote-alias>
            <ordinal>83</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account Category/DMG Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account Category/DMG Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account Category/DMG Name</remote-alias>
            <ordinal>84</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account Email</remote-alias>
            <ordinal>81</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account ID</remote-alias>
            <ordinal>79</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account Name</remote-alias>
            <ordinal>80</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>TravelBox Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[TravelBox Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>TravelBox Account Phone No.</remote-alias>
            <ordinal>82</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Void Type Description</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Void Type Description]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Void Type Description</remote-alias>
            <ordinal>131</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Void Type</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Void Type]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Void Type</remote-alias>
            <ordinal>130</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher Account Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Voucher Account Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher Account Id</remote-alias>
            <ordinal>119</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Voucher Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher Code</remote-alias>
            <ordinal>157</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher Company Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Voucher Company Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher Company Name</remote-alias>
            <ordinal>146</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher DMG Category Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Voucher DMG Category Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher DMG Category Code</remote-alias>
            <ordinal>144</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher DMG Category Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Voucher DMG Category Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher DMG Category Name</remote-alias>
            <ordinal>145</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher Id</remote-name>
            <remote-type>20</remote-type>
            <local-name>[Voucher Id]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher Id</remote-alias>
            <ordinal>118</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>integer</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>1</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Voucher Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Voucher Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Voucher Name</remote-alias>
            <ordinal>158</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>WorkStation Area</remote-name>
            <remote-type>129</remote-type>
            <local-name>[WorkStation Area]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>WorkStation Area</remote-alias>
            <ordinal>132</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>WorkStation Channel</remote-name>
            <remote-type>129</remote-type>
            <local-name>[WorkStation Channel]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>WorkStation Channel</remote-alias>
            <ordinal>133</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>YAS ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[YAS ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>YAS ID</remote-alias>
            <ordinal>63</ordinal>
            <layered>true</layered>
            <caption>MyPass ID</caption>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account Category/DMG Code</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account Category/DMG Code]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account Category/DMG Code</remote-alias>
            <ordinal>89</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account Category/DMG Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account Category/DMG Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account Category/DMG Name</remote-alias>
            <ordinal>90</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account Email</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account Email]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account Email</remote-alias>
            <ordinal>87</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account ID</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account ID]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account ID</remote-alias>
            <ordinal>85</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account Name</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account Name]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account Name</remote-alias>
            <ordinal>86</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Arena Account Phone No.</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Arena Account Phone No.]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Arena Account Phone No.</remote-alias>
            <ordinal>88</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Yas Park Pass</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Yas Park Pass]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Yas Park Pass</remote-alias>
            <ordinal>17</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='column'>
            <remote-name>Zip Pincode</remote-name>
            <remote-type>129</remote-type>
            <local-name>[Zip Pincode]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>Zip Pincode</remote-alias>
            <ordinal>49</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>string</local-type>
            <aggregation>None</aggregation>
            <contains-null>true</contains-null>
            <collation flag='0' name='binary' />
            <attributes>
              <attribute datatype='integer' name='field-type'>2</attribute>
              <attribute datatype='integer' name='role'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='measure'>
            <remote-name>minutes</remote-name>
            <remote-type>5</remote-type>
            <local-name>[minutes]</local-name>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias>minutes</remote-alias>
            <ordinal>181</ordinal>
            <layered>true</layered>
            <family>Custom SQL Query</family>
            <local-type>real</local-type>
            <aggregation>Sum</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='integer' name='field-type'>0</attribute>
            </attributes>
            <object-id>[Migrated Data]</object-id>
          </metadata-record>
          <metadata-record class='capability'>
            <remote-name />
            <remote-type>0</remote-type>
            <parent-name>[sqlproxy]</parent-name>
            <remote-alias />
            <aggregation>Count</aggregation>
            <contains-null>true</contains-null>
            <attributes>
              <attribute datatype='boolean' name='CAP_CREATE_TEMP_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_ALWAYS_USE_LOCAL_MAPPING_TABLES'>false</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_PREFER_LOCAL_MAPPING_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_BLENDING_REMOTE_MAPPING_TABLES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_CASE_INSENSITIVE_CONTAINS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_IGNORE_HINT_CHECK_NOT_NULL'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SORT_BY'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUBQUERIES'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUBQUERY_QUERY_CONTEXT'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUPPORTS_LODJOINS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_SUPPORT_ANALYTIC_FUNCTIONS'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_TOP_N'>true</attribute>
              <attribute datatype='boolean' name='CAP_QUERY_USE_QUERY_FUSION'>true</attribute>
              <attribute datatype='boolean' name='CAP_SUPPORTS_SPLIT_FROM_LEFT'>true</attribute>
              <attribute datatype='boolean' name='CAP_SUPPORTS_SPLIT_FROM_RIGHT'>true</attribute>
              <attribute datatype='integer' name='charset'>0</attribute>
              <attribute datatype='string' name='collation'>&quot;binary&quot;</attribute>
              <attribute datatype='string' name='datasource'>&quot;<![CDATA[<?xml version='1.0' encoding='utf-8' ?>

<datasource :source-version='18.1' formatted-name='Attendance SS (6) (local copy)' inline='true' version='18.1' xmlns:user='http://www.tableausoftware.com/xml/user'>
  <document-format-change-manifest>
    <ObjectModelEncapsulateLegacy />
    <ObjectModelExtractV2 />
    <ObjectModelTableType />
    <SchemaViewerObjectModel />
  </document-format-change-manifest>
  <repository-location derived-from='/t/miralexperiences/datasources/AttendanceSS_15890356801600?rev=2.4' id='AttendanceSS_15890356801600' path='/t/miralexperiences/datasources' revision='1.8' site='miralexperiences' />
  <connection channel='https' class='sqlproxy' dataserver-permissions='true' dbname='AttendanceSS_15890356801600' directory='/dataserver' port='443' server='eu-west-1a.online.tableau.com'>
    <relation name='sqlproxy' table='[sqlproxy]' type='table' />
    <cols>
      <map key='[Account AK]' value='[sqlproxy].[Account AK]' />
      <map key='[Address]' value='[sqlproxy].[Address]' />
      <map key='[Agent CRM Email]' value='[sqlproxy].[Agent CRM Email]' />
      <map key='[Agent CRM ID]' value='[sqlproxy].[Agent CRM ID]' />
      <map key='[Agent CRM Name]' value='[sqlproxy].[Agent CRM Name]' />
      <map key='[Agent CRM Phone No.]' value='[sqlproxy].[Agent CRM Phone No.]' />
      <map key='[Agent OMNI Account Email]' value='[sqlproxy].[Agent OMNI Account Email]' />
      <map key='[Agent OMNI Account ID]' value='[sqlproxy].[Agent OMNI Account ID]' />
      <map key='[Agent OMNI Account Name]' value='[sqlproxy].[Agent OMNI Account Name]' />
      <map key='[Agent OMNI Account Phone No.]' value='[sqlproxy].[Agent OMNI Account Phone No.]' />
      <map key='[Agent Oracle Account ID]' value='[sqlproxy].[Agent Oracle Account ID]' />
      <map key='[Agent TravelBox Account Email]' value='[sqlproxy].[Agent TravelBox Account Email]' />
      <map key='[Agent TravelBox Account ID]' value='[sqlproxy].[Agent TravelBox Account ID]' />
      <map key='[Agent TravelBox Account Name]' value='[sqlproxy].[Agent TravelBox Account Name]' />
      <map key='[Agent TravelBox Account Phone No.]' value='[sqlproxy].[Agent TravelBox Account Phone No.]' />
      <map key='[Agent Yas Arena Account Email]' value='[sqlproxy].[Agent Yas Arena Account Email]' />
      <map key='[Agent Yas Arena Account ID]' value='[sqlproxy].[Agent Yas Arena Account ID]' />
      <map key='[Agent Yas Arena Account Name]' value='[sqlproxy].[Agent Yas Arena Account Name]' />
      <map key='[Agent Yas Arena Account Phone No.]' value='[sqlproxy].[Agent Yas Arena Account Phone No.]' />
      <map key='[Annual Pass Flag]' value='[sqlproxy].[Annual Pass Flag]' />
      <map key='[Attendance Date]' value='[sqlproxy].[Attendance Date]' />
      <map key='[Attendance_Count]' value='[sqlproxy].[Attendance_Count]' />
      <map key='[Attendence Datetime]' value='[sqlproxy].[Attendence Datetime]' />
      <map key='[B2B Account ID]' value='[sqlproxy].[B2B Account ID]' />
      <map key='[Base Media Code]' value='[sqlproxy].[Base Media Code]' />
      <map key='[Base Media ID]' value='[sqlproxy].[Base Media ID]' />
      <map key='[Base Sale Channel]' value='[sqlproxy].[Base Sale Channel]' />
      <map key='[Base Sale ID]' value='[sqlproxy].[Base Sale ID]' />
      <map key='[Base Sale Workstation Area]' value='[sqlproxy].[Base Sale Workstation Area]' />
      <map key='[Base Sale Workstation ID]' value='[sqlproxy].[Base Sale Workstation ID]' />
      <map key='[Base Ticket Code]' value='[sqlproxy].[Base Ticket Code]' />
      <map key='[Base Ticket ID]' value='[sqlproxy].[Base Ticket ID]' />
      <map key='[Budget Attendance]' value='[sqlproxy].[Budget Attendance]' />
      <map key='[CREATED_DATETIME]' value='[sqlproxy].[CREATED_DATETIME]' />
      <map key='[CRM Account DMG Code]' value='[sqlproxy].[CRM Account DMG Code]' />
      <map key='[CRM Account DMG Name]' value='[sqlproxy].[CRM Account DMG Name]' />
      <map key='[CRM Account Email]' value='[sqlproxy].[CRM Account Email]' />
      <map key='[CRM Account ID]' value='[sqlproxy].[CRM Account ID]' />
      <map key='[CRM Account Name]' value='[sqlproxy].[CRM Account Name]' />
      <map key='[CRM Account Phone No.]' value='[sqlproxy].[CRM Account Phone No.]' />
      <map key='[CRM Account SubDMG Code]' value='[sqlproxy].[CRM Account SubDMG Code]' />
      <map key='[CRM Account SubDMG Name]' value='[sqlproxy].[CRM Account SubDMG Name]' />
      <map key='[Calculation_2183682895431348224]' value='[sqlproxy].[Calculation_2183682895431348224]' />
      <map key='[Card Type]' value='[sqlproxy].[Card Type]' />
      <map key='[City]' value='[sqlproxy].[City]' />
      <map key='[Complimentary Product Flag]' value='[sqlproxy].[Complimentary Product Flag]' />
      <map key='[Country of Residence New]' value='[sqlproxy].[Country of Residence New]' />
      <map key='[Country of Residence ]' value='[sqlproxy].[Country of Residence ]' />
      <map key='[Customer Segment]' value='[sqlproxy].[Customer Segment]' />
      <map key='[Customer Type]' value='[sqlproxy].[Customer Type]' />
      <map key='[DRR_Source]' value='[sqlproxy].[DRR_Source]' />
      <map key='[Date of Birth]' value='[sqlproxy].[Date of Birth]' />
      <map key='[Department Code]' value='[sqlproxy].[Department Code]' />
      <map key='[Department Name]' value='[sqlproxy].[Department Name]' />
      <map key='[EH Booking Flow]' value='[sqlproxy].[EH Booking Flow]' />
      <map key='[EH Booking Id]' value='[sqlproxy].[EH Booking Id]' />
      <map key='[EH Channels]' value='[sqlproxy].[EH Channels]' />
      <map key='[EH Client Country Name]' value='[sqlproxy].[EH Client Country Name]' />
      <map key='[EH Client Region Name]' value='[sqlproxy].[EH Client Region Name]' />
      <map key='[EH DMC Flag]' value='[sqlproxy].[EH DMC Flag]' />
      <map key='[EH Segments]' value='[sqlproxy].[EH Segments]' />
      <map key='[EH Sub Channels]' value='[sqlproxy].[EH Sub Channels]' />
      <map key='[Email ]' value='[sqlproxy].[Email ]' />
      <map key='[Emirate State]' value='[sqlproxy].[Emirate State]' />
      <map key='[Etihad ID]' value='[sqlproxy].[Etihad ID]' />
      <map key='[Farah Staff Flag]' value='[sqlproxy].[Farah Staff Flag]' />
      <map key='[Fax Number]' value='[sqlproxy].[Fax Number]' />
      <map key='[First Name]' value='[sqlproxy].[First Name]' />
      <map key='[Forecast Attendance]' value='[sqlproxy].[Forecast Attendance]' />
      <map key='[Forecast Label]' value='[sqlproxy].[Forecast Label]' />
      <map key='[Gate Siteid]' value='[sqlproxy].[Gate Siteid]' />
      <map key='[Gender]' value='[sqlproxy].[Gender]' />
      <map key='[Guest Type]' value='[sqlproxy].[Guest Type]' />
      <map key='[Hopper Flag]' value='[sqlproxy].[Hopper Flag]' />
      <map key='[Industry]' value='[sqlproxy].[Industry]' />
      <map key='[Invoice ID]' value='[sqlproxy].[Invoice ID]' />
      <map key='[Language]' value='[sqlproxy].[Language]' />
      <map key='[Last Name]' value='[sqlproxy].[Last Name]' />
      <map key='[Local/Distant]' value='[sqlproxy].[Local/Distant]' />
      <map key='[MDM ID]' value='[sqlproxy].[MDM ID]' />
      <map key='[Marital Status]' value='[sqlproxy].[Marital Status]' />
      <map key='[Market Segment Based on Segmentation Rule 1]' value='[sqlproxy].[Market Segment Based on Segmentation Rule 1]' />
      <map key='[Market Segment Group 1]' value='[sqlproxy].[Market Segment Group 1]' />
      <map key='[Market Segment Group 2]' value='[sqlproxy].[Market Segment Group 2]' />
      <map key='[Market Segment Segmentation Rule 2]' value='[sqlproxy].[Market Segment Segmentation Rule 2]' />
      <map key='[Media Code]' value='[sqlproxy].[Media Code]' />
      <map key='[Middle Name]' value='[sqlproxy].[Middle Name]' />
      <map key='[Miral Staff Flag]' value='[sqlproxy].[Miral Staff Flag]' />
      <map key='[Miral Staff ID]' value='[sqlproxy].[Miral Staff ID]' />
      <map key='[Mobile Number]' value='[sqlproxy].[Mobile Number]' />
      <map key='[Nationality New]' value='[sqlproxy].[Nationality New]' />
      <map key='[Nationality ]' value='[sqlproxy].[Nationality ]' />
      <map key='[OG Code]' value='[sqlproxy].[OG Code]' />
      <map key='[OG Promotions Group]' value='[sqlproxy].[OG Promotions Group]' />
      <map key='[OG Segment]' value='[sqlproxy].[OG Segment]' />
      <map key='[OG Type Name]' value='[sqlproxy].[OG Type Name]' />
      <map key='[OG Type]' value='[sqlproxy].[OG Type]' />
      <map key='[OMNI Account Category DMG Recursive Name]' value='[sqlproxy].[OMNI Account Category DMG Recursive Name]' />
      <map key='[OMNI Account Category/DMG Code]' value='[sqlproxy].[OMNI Account Category/DMG Code]' />
      <map key='[OMNI Account Category/DMG Name]' value='[sqlproxy].[OMNI Account Category/DMG Name]' />
      <map key='[OMNI Account Company Name]' value='[sqlproxy].[OMNI Account Company Name]' />
      <map key='[OMNI Account Email]' value='[sqlproxy].[OMNI Account Email]' />
      <map key='[OMNI Account ID]' value='[sqlproxy].[OMNI Account ID]' />
      <map key='[OMNI Account Name]' value='[sqlproxy].[OMNI Account Name]' />
      <map key='[OMNI Account Phone No.]' value='[sqlproxy].[OMNI Account Phone No.]' />
      <map key='[OMNI Annual Pass y/n]' value='[sqlproxy].[OMNI Annual Pass y/n]' />
      <map key='[OMNI Multipark y/n]' value='[sqlproxy].[OMNI Multipark y/n]' />
      <map key='[OMNI Park Combination]' value='[sqlproxy].[OMNI Park Combination]' />
      <map key='[OMNI Promotion Code]' value='[sqlproxy].[OMNI Promotion Code]' />
      <map key='[OMNI Promotion Name]' value='[sqlproxy].[OMNI Promotion Name]' />
      <map key='[Occupation]' value='[sqlproxy].[Occupation]' />
      <map key='[Oracle Account ID]' value='[sqlproxy].[Oracle Account ID]' />
      <map key='[Order ID]' value='[sqlproxy].[Order ID]' />
      <map key='[Order Item ID]' value='[sqlproxy].[Order Item ID]' />
      <map key='[P O Box]' value='[sqlproxy].[P O Box]' />
      <map key='[Parent Partner CRM Account ID]' value='[sqlproxy].[Parent Partner CRM Account ID]' />
      <map key='[Parent Partner CRM Account Name]' value='[sqlproxy].[Parent Partner CRM Account Name]' />
      <map key='[Partner Account DMG Code (OMNI) (group)]' value='[sqlproxy].[Partner Account DMG Code (OMNI) (group)]' />
      <map key='[Partner Account DMG Code (OMNI)]' value='[sqlproxy].[Partner Account DMG Code (OMNI)]' />
      <map key='[Partner Account DMG Description (OMNI)]' value='[sqlproxy].[Partner Account DMG Description (OMNI)]' />
      <map key='[Partner Company Account Id (OMNI)]' value='[sqlproxy].[Partner Company Account Id (OMNI)]' />
      <map key='[Partner Company Account Name (OMNI)]' value='[sqlproxy].[Partner Company Account Name (OMNI)]' />
      <map key='[Partner Discount Card Number]' value='[sqlproxy].[Partner Discount Card Number]' />
      <map key='[Partner Discount Expiry Date]' value='[sqlproxy].[Partner Discount Expiry Date]' />
      <map key='[Partner Discount Registration Channel]' value='[sqlproxy].[Partner Discount Registration Channel]' />
      <map key='[Product Category Code]' value='[sqlproxy].[Product Category Code]' />
      <map key='[Product Category Name]' value='[sqlproxy].[Product Category Name]' />
      <map key='[Product Channel]' value='[sqlproxy].[Product Channel]' />
      <map key='[Product Code]' value='[sqlproxy].[Product Code]' />
      <map key='[Product Group]' value='[sqlproxy].[Product Group]' />
      <map key='[Product Name ]' value='[sqlproxy].[Product Name ]' />
      <map key='[Product Sub Category Code]' value='[sqlproxy].[Product Sub Category Code]' />
      <map key='[Product Sub Category Name]' value='[sqlproxy].[Product Sub Category Name]' />
      <map key='[Promotion Classification]' value='[sqlproxy].[Promotion Classification]' />
      <map key='[Promotion DMG Description]' value='[sqlproxy].[Promotion DMG Description]' />
      <map key='[Promotion DMG]' value='[sqlproxy].[Promotion DMG]' />
      <map key='[Promotion Flag]' value='[sqlproxy].[Promotion Flag]' />
      <map key='[Promotion ID]' value='[sqlproxy].[Promotion ID]' />
      <map key='[Promotion Type]' value='[sqlproxy].[Promotion Type]' />
      <map key='[Promotion Valid From]' value='[sqlproxy].[Promotion Valid From]' />
      <map key='[Promotion Valid To]' value='[sqlproxy].[Promotion Valid To]' />
      <map key='[Redemption Company Name]' value='[sqlproxy].[Redemption Company Name]' />
      <map key='[Reservation Id]' value='[sqlproxy].[Reservation Id]' />
      <map key='[SCV ID]' value='[sqlproxy].[SCV ID]' />
      <map key='[Sale Company Name]' value='[sqlproxy].[Sale Company Name]' />
      <map key='[Sale Id]' value='[sqlproxy].[Sale Id]' />
      <map key='[Sale Item Id]' value='[sqlproxy].[Sale Item Id]' />
      <map key='[Sale Transaction Datet]' value='[sqlproxy].[Sale Transaction Datet]' />
      <map key='[Sale Transaction Type Desc]' value='[sqlproxy].[Sale Transaction Type Desc]' />
      <map key='[Sale Transaction Type]' value='[sqlproxy].[Sale Transaction Type]' />
      <map key='[Scan Action]' value='[sqlproxy].[Scan Action]' />
      <map key='[Source Name]' value='[sqlproxy].[Source Name]' />
      <map key='[Ticket Age]' value='[sqlproxy].[Ticket Age]' />
      <map key='[Ticket Code]' value='[sqlproxy].[Ticket Code]' />
      <map key='[Ticket Description]' value='[sqlproxy].[Ticket Description]' />
      <map key='[Ticket Id]' value='[sqlproxy].[Ticket Id]' />
      <map key='[Ticket Market]' value='[sqlproxy].[Ticket Market]' />
      <map key='[Ticket Tier]' value='[sqlproxy].[Ticket Tier]' />
      <map key='[Ticket Type]' value='[sqlproxy].[Ticket Type]' />
      <map key='[Ticket or Product Flag]' value='[sqlproxy].[Ticket or Product Flag]' />
      <map key='[Title]' value='[sqlproxy].[Title]' />
      <map key='[Transaction ID]' value='[sqlproxy].[Transaction ID]' />
      <map key='[TravelBox Account Category/DMG Code]' value='[sqlproxy].[TravelBox Account Category/DMG Code]' />
      <map key='[TravelBox Account Category/DMG Name]' value='[sqlproxy].[TravelBox Account Category/DMG Name]' />
      <map key='[TravelBox Account Email]' value='[sqlproxy].[TravelBox Account Email]' />
      <map key='[TravelBox Account ID]' value='[sqlproxy].[TravelBox Account ID]' />
      <map key='[TravelBox Account Name]' value='[sqlproxy].[TravelBox Account Name]' />
      <map key='[TravelBox Account Phone No.]' value='[sqlproxy].[TravelBox Account Phone No.]' />
      <map key='[Void Type Description]' value='[sqlproxy].[Void Type Description]' />
      <map key='[Void Type]' value='[sqlproxy].[Void Type]' />
      <map key='[Voucher Account Id]' value='[sqlproxy].[Voucher Account Id]' />
      <map key='[Voucher Code]' value='[sqlproxy].[Voucher Code]' />
      <map key='[Voucher Company Name]' value='[sqlproxy].[Voucher Company Name]' />
      <map key='[Voucher DMG Category Code]' value='[sqlproxy].[Voucher DMG Category Code]' />
      <map key='[Voucher DMG Category Name]' value='[sqlproxy].[Voucher DMG Category Name]' />
      <map key='[Voucher Id]' value='[sqlproxy].[Voucher Id]' />
      <map key='[Voucher Name]' value='[sqlproxy].[Voucher Name]' />
      <map key='[WorkStation Area]' value='[sqlproxy].[WorkStation Area]' />
      <map key='[WorkStation Channel]' value='[sqlproxy].[WorkStation Channel]' />
      <map key='[YAS ID]' value='[sqlproxy].[YAS ID]' />
      <map key='[Yas Arena Account Category/DMG Code]' value='[sqlproxy].[Yas Arena Account Category/DMG Code]' />
      <map key='[Yas Arena Account Category/DMG Name]' value='[sqlproxy].[Yas Arena Account Category/DMG Name]' />
      <map key='[Yas Arena Account Email]' value='[sqlproxy].[Yas Arena Account Email]' />
      <map key='[Yas Arena Account ID]' value='[sqlproxy].[Yas Arena Account ID]' />
      <map key='[Yas Arena Account Name]' value='[sqlproxy].[Yas Arena Account Name]' />
      <map key='[Yas Arena Account Phone No.]' value='[sqlproxy].[Yas Arena Account Phone No.]' />
      <map key='[Yas Park Pass]' value='[sqlproxy].[Yas Park Pass]' />
      <map key='[Zip Pincode]' value='[sqlproxy].[Zip Pincode]' />
      <map key='[minutes]' value='[sqlproxy].[minutes]' />
    </cols>
  </connection>
  <aliases enabled='yes' />
  <column aggregation='Count' caption='Annual Pass/Seasonal Pass Flag' datatype='string' default-type='nominal' name='[Annual Pass Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Attendance Date Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-format='n\#,\#\#0;-\#,\#\#0' default-type='quantitative' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='Year' datatype='datetime' default-format='*m/d/yyyy hh:nn:ss' default-type='ordinal' name='[Attendence Datetime]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[B2b Agent Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[B2b Partner Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Base Media ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' caption='Base Sale ID/Invoice ID' datatype='integer' default-type='ordinal' name='[Base Sale ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Base Ticket ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-type='quantitative' hidden='true' name='[Budget Amount]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-format='n\#,\#\#0;-\#,\#\#0' default-type='quantitative' name='[Budget Attendance]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='User' caption='Attendance Count' datatype='integer' default-format='n\#,\#\#0;-\#,\#\#0' default-type='quantitative' hidden='true' name='[Calculation_2183682895431348224]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
    <calculation class='tableau' formula='COUNT([Ticket Id])' />
    <desc>
      <formatted-text>
        <run fontname='Tableau Medium' fontsize='8'>Deprecated- To be removed</run>
      </formatted-text>
    </desc>
  </column>
  <column aggregation='None' datatype='string' default-type='nominal' name='[City]' pivot='key' role='dimension' semantic-role='[City].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' name='[Country of Residence New]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='None' datatype='string' default-type='nominal' name='[Country of Residence ]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Year' datatype='date' datatype-customized='true' default-type='ordinal' name='[Date of Birth]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Department Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[EH Booking Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' name='[EH Client Country Name]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='None' datatype='string' default-type='nominal' name='[Emirate State]' pivot='key' role='dimension' semantic-role='[State].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-format='n\#,\#\#0;-\#,\#\#0' default-type='quantitative' name='[Forecast Attendance]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Gate Siteid]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[IG Discount Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[IG Discount Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Market Segment Segmentation Rule 1' datatype='string' default-type='nominal' name='[Market Segment Based on Segmentation Rule 1]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Media Code/Voucher Code' datatype='string' default-type='nominal' name='[Media Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Category DMG Recursive Name' datatype='string' default-type='nominal' name='[OMNI Account Category DMG Recursive Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Category/DMG Code' datatype='string' default-type='nominal' name='[OMNI Account Category/DMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Category/DMG Name' datatype='string' default-type='nominal' name='[OMNI Account Category/DMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Company Name' datatype='string' default-type='nominal' name='[OMNI Account Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Email' datatype='string' default-type='nominal' name='[OMNI Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' caption='Account ID' datatype='integer' default-type='ordinal' name='[OMNI Account ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Account Name' datatype='string' default-type='nominal' name='[OMNI Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Account Phone No.' datatype='string' default-type='nominal' name='[OMNI Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Promotion Code' datatype='string' default-type='nominal' name='[OMNI Promotion Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Promotion Name' datatype='string' default-type='nominal' name='[OMNI Promotion Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-type='quantitative' hidden='true' name='[Offer Amount]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='Sum' datatype='real' default-type='quantitative' hidden='true' name='[Offer Percentage]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
  <column aggregation='Count' caption='B2B Y/N' datatype='string' default-type='nominal' name='[Partner Account DMG Code (OMNI) (group)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
    <calculation class='categorical-bin' column='[Partner Account DMG Code (OMNI)]' default='&quot;Other&quot;' new-bin='true'>
      <bin default-name='false' value='&quot;B2B&quot;'>
        <value>&quot;AGENCY&quot;</value>
        <value>&quot;CORP&quot;</value>
        <value>&quot;EHPF&quot;</value>
        <value>&quot;GOV&quot;</value>
        <value>&quot;HTL&quot;</value>
        <value>&quot;INT&quot;</value>
        <value>&quot;SCH&quot;</value>
        <value>&quot;SHH&quot;</value>
        <value>&quot;TO&quot;</value>
        <value>&quot;TODMC&quot;</value>
        <value>&quot;TOINT&quot;</value>
        <value>&quot;WAFFER&quot;</value>
        <value>&quot;YASSTH&quot;</value>
      </bin>
    </calculation>
  </column>
  <column aggregation='Count' caption='Partner Account DMG Code' datatype='string' default-type='nominal' name='[Partner Account DMG Code (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Partner Account DMG Description' datatype='string' default-type='nominal' name='[Partner Account DMG Description (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Partner Company Account Id' datatype='string' default-type='nominal' name='[Partner Company Account Id (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Partner Company Account Name' datatype='string' default-type='nominal' name='[Partner Company Account Name (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Product Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Promotion Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[Redemption Company Code ]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Redemption Company Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Ticket Use Facility' datatype='string' default-type='nominal' name='[Redemption Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' caption='Reservation Id/Invoice No. ' datatype='integer' default-type='ordinal' name='[Reservation Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[Sale Company Code ]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Sale Company Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='Ticket Sale Facility' datatype='string' default-type='nominal' name='[Sale Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' caption='Sale ID/Invoice ID' datatype='integer' default-type='ordinal' name='[Sale Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' caption='Sale Item ID/Invoice Item ID' datatype='integer' default-type='ordinal' name='[Sale Item Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Year' caption='Sale Transaction Date' datatype='date' default-type='ordinal' name='[Sale Transaction Datet]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='quantitative' hidden='true' name='[Sale Transaction Datetime Key]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Sale Transaction Type]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' datatype='string' default-type='nominal' hidden='true' name='[Status]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Sum' caption='Ticket ID/Voucher ID' datatype='integer' default-type='ordinal' name='[Ticket Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Transaction ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Void Type]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Voucher Account Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Sum' datatype='integer' default-type='ordinal' name='[Voucher Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
  <column aggregation='Count' caption='MyPass ID' datatype='string' default-type='nominal' name='[YAS ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='None' datatype='string' default-type='nominal' name='[Zip Pincode]' pivot='key' role='dimension' semantic-role='[ZipCode].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
  <column aggregation='Count' caption='Migrated Data' datatype='table' default-type='quantitative' hidden='true' name='[__tableau_internal_object_id__].[Migrated Data]' pivot='key' role='measure' type='quantitative' user-datatype='table' visual-totals='Default' />
  <folders-common>
    <folder name='01 - Date/Time'>
      <folder-item name='[Attendance Date]' type='field' />
      <folder-item name='[Attendence Datetime]' type='field' />
      <folder-item name='[Date of Birth]' type='field' />
      <folder-item name='[Sale Transaction Datet]' type='field' />
    </folder>
    <folder name='02 - Facility'>
      <folder-item name='[Redemption Company Name]' type='field' />
      <folder-item name='[Sale Company Name]' type='field' />
    </folder>
    <folder name='03 - Product'>
      <folder-item name='[Annual Pass Flag]' type='field' />
      <folder-item name='[Complimentary Product Flag]' type='field' />
      <folder-item name='[Hopper Flag]' type='field' />
      <folder-item name='[OMNI Annual Pass y/n]' type='field' />
      <folder-item name='[Product Category Code]' type='field' />
      <folder-item name='[Product Category Name]' type='field' />
      <folder-item name='[Product Channel]' type='field' />
      <folder-item name='[Product Code]' type='field' />
      <folder-item name='[Product Group]' type='field' />
      <folder-item name='[Product Name ]' type='field' />
      <folder-item name='[Product Sub Category Code]' type='field' />
      <folder-item name='[Product Sub Category Name]' type='field' />
      <folder-item name='[Ticket Age]' type='field' />
      <folder-item name='[Ticket Code]' type='field' />
      <folder-item name='[Ticket Description]' type='field' />
      <folder-item name='[Ticket Market]' type='field' />
      <folder-item name='[Ticket Tier]' type='field' />
      <folder-item name='[Ticket Type]' type='field' />
      <folder-item name='[Ticket or Product Flag]' type='field' />
      <folder-item name='[Yas Park Pass]' type='field' />
    </folder>
    <folder name='04 - Department'>
      <folder-item name='[Department Code]' type='field' />
      <folder-item name='[Department Name]' type='field' />
    </folder>
    <folder name='05 - Segmentation'>
      <folder-item name='[EH Channels]' type='field' />
      <folder-item name='[EH Segments]' type='field' />
      <folder-item name='[EH Sub Channels]' type='field' />
      <folder-item name='[Market Segment Based on Segmentation Rule 1]' type='field' />
      <folder-item name='[Market Segment Group 1]' type='field' />
      <folder-item name='[Market Segment Group 2]' type='field' />
      <folder-item name='[Market Segment Segmentation Rule 2]' type='field' />
    </folder>
    <folder name='08 - Sale Detail'>
      <folder-item name='[Base Media Code]' type='field' />
      <folder-item name='[Base Media ID]' type='field' />
      <folder-item name='[Base Sale Channel]' type='field' />
      <folder-item name='[Base Sale ID]' type='field' />
      <folder-item name='[Base Sale Workstation Area]' type='field' />
      <folder-item name='[Base Sale Workstation ID]' type='field' />
      <folder-item name='[Base Ticket Code]' type='field' />
      <folder-item name='[Base Ticket ID]' type='field' />
      <folder-item name='[EH Booking Flow]' type='field' />
      <folder-item name='[EH Booking Id]' type='field' />
      <folder-item name='[Media Code]' type='field' />
      <folder-item name='[Reservation Id]' type='field' />
      <folder-item name='[Sale Id]' type='field' />
      <folder-item name='[Sale Item Id]' type='field' />
      <folder-item name='[Sale Transaction Type Desc]' type='field' />
      <folder-item name='[Sale Transaction Type]' type='field' />
      <folder-item name='[Ticket Id]' type='field' />
      <folder-item name='[Transaction ID]' type='field' />
      <folder-item name='[Void Type Description]' type='field' />
      <folder-item name='[Void Type]' type='field' />
      <folder-item name='[Voucher Account Id]' type='field' />
      <folder-item name='[Voucher Id]' type='field' />
      <folder-item name='[WorkStation Area]' type='field' />
      <folder-item name='[WorkStation Channel]' type='field' />
    </folder>
    <folder name='10 - Promotion'>
      <folder-item name='[OMNI Promotion Code]' type='field' />
      <folder-item name='[OMNI Promotion Name]' type='field' />
      <folder-item name='[Promotion Classification]' type='field' />
      <folder-item name='[Promotion DMG Description]' type='field' />
      <folder-item name='[Promotion DMG]' type='field' />
      <folder-item name='[Promotion Flag]' type='field' />
      <folder-item name='[Promotion ID]' type='field' />
      <folder-item name='[Promotion Type]' type='field' />
      <folder-item name='[Promotion Valid From]' type='field' />
      <folder-item name='[Promotion Valid To]' type='field' />
    </folder>
    <folder name='11 - Attendance'>
      <folder-item name='[Gate Siteid]' type='field' />
      <folder-item name='[Scan Action]' type='field' />
    </folder>
    <folder name='11 - Guest Information'>
      <folder-item name='[Account AK]' type='field' />
      <folder-item name='[Address]' type='field' />
      <folder-item name='[City]' type='field' />
      <folder-item name='[Country of Residence New]' type='field' />
      <folder-item name='[Country of Residence ]' type='field' />
      <folder-item name='[Customer Segment]' type='field' />
      <folder-item name='[Customer Type]' type='field' />
      <folder-item name='[EH Client Country Name]' type='field' />
      <folder-item name='[Email ]' type='field' />
      <folder-item name='[Emirate State]' type='field' />
      <folder-item name='[Etihad ID]' type='field' />
      <folder-item name='[Farah Staff Flag]' type='field' />
      <folder-item name='[Fax Number]' type='field' />
      <folder-item name='[First Name]' type='field' />
      <folder-item name='[Gender]' type='field' />
      <folder-item name='[Guest Type]' type='field' />
      <folder-item name='[Industry]' type='field' />
      <folder-item name='[Language]' type='field' />
      <folder-item name='[Last Name]' type='field' />
      <folder-item name='[Local/Distant]' type='field' />
      <folder-item name='[MDM ID]' type='field' />
      <folder-item name='[Marital Status]' type='field' />
      <folder-item name='[Middle Name]' type='field' />
      <folder-item name='[Miral Staff Flag]' type='field' />
      <folder-item name='[Miral Staff ID]' type='field' />
      <folder-item name='[Mobile Number]' type='field' />
      <folder-item name='[Nationality New]' type='field' />
      <folder-item name='[Nationality ]' type='field' />
      <folder-item name='[Occupation]' type='field' />
      <folder-item name='[Oracle Account ID]' type='field' />
      <folder-item name='[P O Box]' type='field' />
      <folder-item name='[Parent Partner CRM Account ID]' type='field' />
      <folder-item name='[Parent Partner CRM Account Name]' type='field' />
      <folder-item name='[SCV ID]' type='field' />
      <folder-item name='[Title]' type='field' />
      <folder-item name='[YAS ID]' type='field' />
      <folder-item name='[Zip Pincode]' type='field' />
    </folder>
    <folder name='12 - Partner Information'>
      <folder-item name='[B2B Account ID]' type='field' />
      <folder-item name='[EH Client Region Name]' type='field' />
      <folder-item name='[EH DMC Flag]' type='field' />
      <folder-item name='[OMNI Account Category DMG Recursive Name]' type='field' />
      <folder-item name='[OMNI Account Category/DMG Code]' type='field' />
      <folder-item name='[OMNI Account Category/DMG Name]' type='field' />
      <folder-item name='[OMNI Account Company Name]' type='field' />
      <folder-item name='[OMNI Account Email]' type='field' />
      <folder-item name='[OMNI Account ID]' type='field' />
      <folder-item name='[OMNI Account Name]' type='field' />
      <folder-item name='[OMNI Account Phone No.]' type='field' />
      <folder-item name='[OMNI Multipark y/n]' type='field' />
      <folder-item name='[OMNI Park Combination]' type='field' />
      <folder-item name='[Partner Account DMG Code (OMNI) (group)]' type='field' />
      <folder-item name='[Partner Account DMG Code (OMNI)]' type='field' />
      <folder-item name='[Partner Account DMG Description (OMNI)]' type='field' />
      <folder-item name='[Partner Company Account Id (OMNI)]' type='field' />
      <folder-item name='[Partner Company Account Name (OMNI)]' type='field' />
    </folder>
    <folder name='12.1 - CRM'>
      <folder-item name='[CRM Account DMG Code]' type='field' />
      <folder-item name='[CRM Account DMG Name]' type='field' />
      <folder-item name='[CRM Account Email]' type='field' />
      <folder-item name='[CRM Account ID]' type='field' />
      <folder-item name='[CRM Account Name]' type='field' />
      <folder-item name='[CRM Account Phone No.]' type='field' />
      <folder-item name='[CRM Account SubDMG Code]' type='field' />
      <folder-item name='[CRM Account SubDMG Name]' type='field' />
    </folder>
    <folder name='12.2 - Agent'>
      <folder-item name='[Agent CRM Email]' type='field' />
      <folder-item name='[Agent CRM ID]' type='field' />
      <folder-item name='[Agent CRM Name]' type='field' />
      <folder-item name='[Agent CRM Phone No.]' type='field' />
      <folder-item name='[Agent OMNI Account Email]' type='field' />
      <folder-item name='[Agent OMNI Account ID]' type='field' />
      <folder-item name='[Agent OMNI Account Name]' type='field' />
      <folder-item name='[Agent OMNI Account Phone No.]' type='field' />
      <folder-item name='[Agent Oracle Account ID]' type='field' />
      <folder-item name='[Agent TravelBox Account Email]' type='field' />
      <folder-item name='[Agent TravelBox Account ID]' type='field' />
      <folder-item name='[Agent TravelBox Account Name]' type='field' />
      <folder-item name='[Agent TravelBox Account Phone No.]' type='field' />
      <folder-item name='[Agent Yas Arena Account Email]' type='field' />
      <folder-item name='[Agent Yas Arena Account ID]' type='field' />
      <folder-item name='[Agent Yas Arena Account Name]' type='field' />
      <folder-item name='[Agent Yas Arena Account Phone No.]' type='field' />
    </folder>
    <folder name='12.3 TravelBox'>
      <folder-item name='[TravelBox Account Category/DMG Code]' type='field' />
      <folder-item name='[TravelBox Account Category/DMG Name]' type='field' />
      <folder-item name='[TravelBox Account Email]' type='field' />
      <folder-item name='[TravelBox Account ID]' type='field' />
      <folder-item name='[TravelBox Account Name]' type='field' />
      <folder-item name='[TravelBox Account Phone No.]' type='field' />
    </folder>
    <folder name='12.4 Yas Arena'>
      <folder-item name='[Yas Arena Account Category/DMG Code]' type='field' />
      <folder-item name='[Yas Arena Account Category/DMG Name]' type='field' />
      <folder-item name='[Yas Arena Account Email]' type='field' />
      <folder-item name='[Yas Arena Account ID]' type='field' />
      <folder-item name='[Yas Arena Account Name]' type='field' />
      <folder-item name='[Yas Arena Account Phone No.]' type='field' />
    </folder>
    <folder name='13 - Vouchers'>
      <folder-item name='[Voucher Code]' type='field' />
      <folder-item name='[Voucher Company Name]' type='field' />
      <folder-item name='[Voucher DMG Category Code]' type='field' />
      <folder-item name='[Voucher DMG Category Name]' type='field' />
      <folder-item name='[Voucher Name]' type='field' />
    </folder>
    <folder name='14 - Source'>
      <folder-item name='[Source Name]' type='field' />
    </folder>
    <folder name='15 - Partner Discount'>
      <folder-item name='[Card Type]' type='field' />
      <folder-item name='[Partner Discount Card Number]' type='field' />
      <folder-item name='[Partner Discount Expiry Date]' type='field' />
      <folder-item name='[Partner Discount Registration Channel]' type='field' />
    </folder>
    <folder name='Measures 01 - Attendance'>
      <folder-item name='[Attendance_Count]' type='field' />
      <folder-item name='[Budget Attendance]' type='field' />
      <folder-item name='[Calculation_2183682895431348224]' type='field' />
      <folder-item name='[Forecast Attendance]' type='field' />
      <folder-item name='[Forecast Label]' type='field' />
    </folder>
  </folders-common>
  <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-structure='false' />
  <semantic-values>
    <semantic-value key='[Country].[Name]' value='&quot;United States&quot;' />
  </semantic-values>
  <object-graph>
    <objects>
      <object caption='Migrated Data' id='Migrated Data'>
        <properties context=''>
          <relation name='sqlproxy' table='[sqlproxy]' type='table' />
        </properties>
      </object>
    </objects>
  </object-graph>
</datasource>
]]>&quot;</attribute>
              <attribute datatype='string' name='dialect-definition'>&quot;<![CDATA[<dialect-definition>
  <primary-dialect class='hyper' version='0.0.0'>
  </primary-dialect>
</dialect-definition>
]]>&quot;</attribute>
              <attribute datatype='boolean' name='extract-active'>true</attribute>
              <attribute datatype='boolean' name='fast-get-server-time'>true</attribute>
              <attribute datatype='string' name='update-time'>&quot;7/17/2024 3:40:30 AM&quot;</attribute>
            </attributes>
          </metadata-record>
        </metadata-records>
      </connection>
      <overridable-settings>
        <date-options fiscal-year-start='january' start-of-week='sunday' />
        <default-date-format />
        <default-calendar-type>Gregorian</default-calendar-type>
      </overridable-settings>
      <aliases enabled='yes' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Account AK]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Address]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent CRM Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent CRM ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent CRM Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent CRM Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent OMNI Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent OMNI Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent OMNI Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent OMNI Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent Oracle Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent TravelBox Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent TravelBox Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent TravelBox Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent TravelBox Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent Yas Arena Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent Yas Arena Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent Yas Arena Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Agent Yas Arena Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Annual Pass/Seasonal Pass Flag' datatype='string' default-type='nominal' layered='true' name='[Annual Pass Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column datatype='string' name='[Attendance Date (Weekdays) (group)]' role='dimension' type='nominal'>
        <calculation class='categorical-bin' column='[Attendance Date (Weekdays)]' new-bin='true'>
          <bin default-name='false' value='&quot;WD&quot;'>
            <value>1</value>
            <value>2</value>
            <value>3</value>
            <value>4</value>
          </bin>
          <bin default-name='false' value='&quot;WE&quot;'>
            <value>5</value>
            <value>6</value>
            <value>7</value>
          </bin>
        </calculation>
      </column>
      <column aggregation='Sum' datatype='integer' name='[Attendance Date (Weekdays)]' role='dimension' type='ordinal' user:agg-type='Weekday' user:base-field='Attendance Date' user:ui-builder='date-bin-builder'>
        <calculation class='tableau' formula='DATEPART(&apos;weekday&apos;, [Attendance Date])' />
      </column>
      <column aggregation='Year' datatype='date' default-type='ordinal' layered='true' name='[Attendance Date]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
      <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
        <desc>
          <formatted-text>
            <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
          </formatted-text>
        </desc>
      </column>
      <column aggregation='Year' datatype='datetime' default-format='*m/d/yyyy hh:nn:ss' default-type='ordinal' layered='true' name='[Attendence Datetime]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[B2B Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Base Media Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Base Media ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Base Sale Channel]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' caption='Base Sale ID/Invoice ID' datatype='integer' default-type='ordinal' layered='true' name='[Base Sale ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Base Sale Workstation Area]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Base Sale Workstation ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Base Ticket Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Base Ticket ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Sum' datatype='real' default-format='n#,##0;-#,##0' default-type='quantitative' layered='true' name='[Budget Attendance]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
      <column aggregation='Year' datatype='datetime' default-type='ordinal' layered='true' name='[CREATED_DATETIME]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account DMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account DMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account SubDMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[CRM Account SubDMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column caption='Number of Records' datatype='integer' name='[Calculation_1728537845590171648]' role='measure' type='quantitative'>
        <calculation class='tableau' formula='if not isnull([Ticket Id]) then 1 end' />
      </column>
      <column caption='Nationality New Var' datatype='string' name='[Calculation_2241103796129898496]' role='dimension' type='nominal'>
        <calculation class='tableau' formula='CASE [Ticket Id]&#13;&#10;&#13;&#10;When    7343604  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7343900  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7343901  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7343902  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7343903  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7344258  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7344259  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7344263  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7344264  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7346144  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7346145  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7346147  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7346149  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7348558  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7348559  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7358087  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7358709  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7358710  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7358776  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7358778  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7367599  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7367771  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7374719  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7387523  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7387524  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7389247  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7410921  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7434797  Then     &quot;Info Not Provided&quot;&#13;&#10;When    7434798  Then     &quot;Info Not Provided&quot;&#13;&#10;&#13;&#10;ELSE&#13;&#10;[Nationality New]&#13;&#10;END' />
      </column>
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Card Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='None' datatype='string' default-type='nominal' layered='true' name='[City]' pivot='key' role='dimension' semantic-role='[City].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Complimentary Product Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Country of Residence New]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='None' datatype='string' default-type='nominal' layered='true' name='[Country of Residence ]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Customer Segment]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Customer Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[DRR_Source]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Year' datatype='date' datatype-customized='true' default-type='ordinal' layered='true' name='[Date of Birth]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Department Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Department Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Booking Flow]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[EH Booking Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Channels]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Client Country Name]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Client Region Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH DMC Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Segments]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[EH Sub Channels]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Email ]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='None' datatype='string' default-type='nominal' layered='true' name='[Emirate State]' pivot='key' role='dimension' semantic-role='[State].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Etihad ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Farah Staff Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Fax Number]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[First Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='real' default-format='n#,##0;-#,##0' default-type='quantitative' layered='true' name='[Forecast Attendance]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Forecast Label]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Gate Siteid]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Gender]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Guest Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Hopper Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Industry]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Invoice ID]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Language]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Last Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Local/Distant]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[MDM ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Marital Status]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Market Segment Segmentation Rule 1' datatype='string' default-type='nominal' layered='true' name='[Market Segment Based on Segmentation Rule 1]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Market Segment Group 1]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Market Segment Group 2]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Market Segment Segmentation Rule 2]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Media Code/Voucher Code' datatype='string' default-type='nominal' layered='true' name='[Media Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Middle Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Miral Staff Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Miral Staff ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Mobile Number]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column datatype='string' name='[Nationality New Var (group)]' role='dimension' type='nominal'>
        <calculation class='categorical-bin' column='[Calculation_2241103796129898496]' new-bin='true'>
          <bin default-name='false' value='&quot;Info Not Provided&quot;'>
            <value>&quot;Info Not Provided&quot;</value>
            <value>&quot;Info not provided&quot;</value>
          </bin>
        </calculation>
      </column>
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Nationality New]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Nationality ]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OG Promotions Group]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OG Segment]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OG Type Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OG Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Category DMG Recursive Name' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Category DMG Recursive Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Category/DMG Code' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Category/DMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Category/DMG Name' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Category/DMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Company Name' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Email' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' caption='Account ID' datatype='integer' default-type='ordinal' layered='true' name='[OMNI Account ID]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' caption='Account Name' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Account Phone No.' datatype='string' default-type='nominal' layered='true' name='[OMNI Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OMNI Annual Pass y/n]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OMNI Multipark y/n]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[OMNI Park Combination]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Promotion Code' datatype='string' default-type='nominal' layered='true' name='[OMNI Promotion Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Promotion Name' datatype='string' default-type='nominal' layered='true' name='[OMNI Promotion Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Occupation]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Oracle Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Order ID]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Order Item ID]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[P O Box]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Parent Partner CRM Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Parent Partner CRM Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='B2B Y/N' datatype='string' default-type='nominal' layered='true' name='[Partner Account DMG Code (OMNI) (group)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <calculation class='categorical-bin' column='[Partner Account DMG Code (OMNI)]' default='&quot;Other&quot;' new-bin='true'>
          <bin default-name='false' value='&quot;B2B&quot;'>
            <value>&quot;AGENCY&quot;</value>
            <value>&quot;CORP&quot;</value>
            <value>&quot;EHPF&quot;</value>
            <value>&quot;GOV&quot;</value>
            <value>&quot;HTL&quot;</value>
            <value>&quot;INT&quot;</value>
            <value>&quot;SCH&quot;</value>
            <value>&quot;SHH&quot;</value>
            <value>&quot;TO&quot;</value>
            <value>&quot;TODMC&quot;</value>
            <value>&quot;TOINT&quot;</value>
            <value>&quot;WAFFER&quot;</value>
            <value>&quot;YASSTH&quot;</value>
          </bin>
        </calculation>
      </column>
      <column aggregation='Count' caption='Partner Account DMG Code' datatype='string' default-type='nominal' layered='true' name='[Partner Account DMG Code (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Partner Account DMG Description' datatype='string' default-type='nominal' layered='true' name='[Partner Account DMG Description (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Partner Company Account Id' datatype='string' default-type='nominal' layered='true' name='[Partner Company Account Id (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Partner Company Account Name' datatype='string' default-type='nominal' layered='true' name='[Partner Company Account Name (OMNI)]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Partner Discount Card Number]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Year' datatype='datetime' default-type='ordinal' layered='true' name='[Partner Discount Expiry Date]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Partner Discount Registration Channel]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Category Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Category Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Channel]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Group]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Name ]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Sub Category Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Product Sub Category Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion Classification]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion DMG Description]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion DMG]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Promotion Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Year' datatype='datetime' default-type='ordinal' layered='true' name='[Promotion Valid From]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Year' datatype='datetime' default-type='ordinal' layered='true' name='[Promotion Valid To]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column aggregation='Count' caption='Ticket Use Facility' datatype='string' default-type='nominal' layered='true' name='[Redemption Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' caption='Reservation Id/Invoice No. ' datatype='integer' default-type='ordinal' layered='true' name='[Reservation Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[SCV ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='Ticket Sale Facility' datatype='string' default-type='nominal' layered='true' name='[Sale Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' caption='Sale ID/Invoice ID' datatype='integer' default-type='ordinal' layered='true' name='[Sale Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Sum' caption='Sale Item ID/Invoice Item ID' datatype='integer' default-type='ordinal' layered='true' name='[Sale Item Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Year' caption='Sale Transaction Date' datatype='date' default-type='ordinal' layered='true' name='[Sale Transaction Datet]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Sale Transaction Type Desc]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Sale Transaction Type]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Scan Action]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Source Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Age]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Description]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' caption='Ticket ID/Voucher ID' datatype='integer' default-type='ordinal' layered='true' name='[Ticket Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Market]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Tier]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket Type]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Ticket or Product Flag]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Title]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Transaction ID]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account Category/DMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account Category/DMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[TravelBox Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Void Type Description]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Void Type]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Voucher Account Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Voucher Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Voucher Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Voucher DMG Category Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Voucher DMG Category Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='integer' default-type='ordinal' layered='true' name='[Voucher Id]' pivot='key' role='dimension' type='ordinal' user-datatype='integer' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Voucher Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[WorkStation Area]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[WorkStation Channel]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' caption='MyPass ID' datatype='string' default-type='nominal' layered='true' name='[YAS ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account Category/DMG Code]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account Category/DMG Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account Email]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account ID]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Arena Account Phone No.]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Count' datatype='string' default-type='nominal' layered='true' name='[Yas Park Pass]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='None' datatype='string' default-type='nominal' layered='true' name='[Zip Pincode]' pivot='key' role='dimension' semantic-role='[ZipCode].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
      <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[minutes]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default' />
      <folders-common>
        <folder layered='true' name='01 - Date/Time'>
          <folder-item name='[Attendance Date]' type='field' />
          <folder-item name='[Attendence Datetime]' type='field' />
          <folder-item name='[Date of Birth]' type='field' />
          <folder-item name='[Sale Transaction Datet]' type='field' />
        </folder>
        <folder layered='true' name='02 - Facility'>
          <folder-item name='[Redemption Company Name]' type='field' />
          <folder-item name='[Sale Company Name]' type='field' />
        </folder>
        <folder layered='true' name='03 - Product'>
          <folder-item name='[Annual Pass Flag]' type='field' />
          <folder-item name='[Complimentary Product Flag]' type='field' />
          <folder-item name='[Hopper Flag]' type='field' />
          <folder-item name='[OMNI Annual Pass y/n]' type='field' />
          <folder-item name='[Product Category Code]' type='field' />
          <folder-item name='[Product Category Name]' type='field' />
          <folder-item name='[Product Channel]' type='field' />
          <folder-item name='[Product Code]' type='field' />
          <folder-item name='[Product Group]' type='field' />
          <folder-item name='[Product Name ]' type='field' />
          <folder-item name='[Product Sub Category Code]' type='field' />
          <folder-item name='[Product Sub Category Name]' type='field' />
          <folder-item name='[Ticket Age]' type='field' />
          <folder-item name='[Ticket Code]' type='field' />
          <folder-item name='[Ticket Description]' type='field' />
          <folder-item name='[Ticket Market]' type='field' />
          <folder-item name='[Ticket Tier]' type='field' />
          <folder-item name='[Ticket Type]' type='field' />
          <folder-item name='[Ticket or Product Flag]' type='field' />
          <folder-item name='[Yas Park Pass]' type='field' />
        </folder>
        <folder layered='true' name='04 - Department'>
          <folder-item name='[Department Code]' type='field' />
          <folder-item name='[Department Name]' type='field' />
        </folder>
        <folder layered='true' name='05 - Segmentation'>
          <folder-item name='[EH Channels]' type='field' />
          <folder-item name='[EH Segments]' type='field' />
          <folder-item name='[EH Sub Channels]' type='field' />
          <folder-item name='[Market Segment Based on Segmentation Rule 1]' type='field' />
          <folder-item name='[Market Segment Group 1]' type='field' />
          <folder-item name='[Market Segment Group 2]' type='field' />
          <folder-item name='[Market Segment Segmentation Rule 2]' type='field' />
        </folder>
        <folder layered='true' name='08 - Sale Detail'>
          <folder-item name='[Base Media Code]' type='field' />
          <folder-item name='[Base Media ID]' type='field' />
          <folder-item name='[Base Sale Channel]' type='field' />
          <folder-item name='[Base Sale ID]' type='field' />
          <folder-item name='[Base Sale Workstation Area]' type='field' />
          <folder-item name='[Base Sale Workstation ID]' type='field' />
          <folder-item name='[Base Ticket Code]' type='field' />
          <folder-item name='[Base Ticket ID]' type='field' />
          <folder-item name='[EH Booking Flow]' type='field' />
          <folder-item name='[EH Booking Id]' type='field' />
          <folder-item name='[Media Code]' type='field' />
          <folder-item name='[Reservation Id]' type='field' />
          <folder-item name='[Sale Id]' type='field' />
          <folder-item name='[Sale Item Id]' type='field' />
          <folder-item name='[Sale Transaction Type Desc]' type='field' />
          <folder-item name='[Sale Transaction Type]' type='field' />
          <folder-item name='[Ticket Id]' type='field' />
          <folder-item name='[Transaction ID]' type='field' />
          <folder-item name='[Void Type Description]' type='field' />
          <folder-item name='[Void Type]' type='field' />
          <folder-item name='[Voucher Account Id]' type='field' />
          <folder-item name='[Voucher Id]' type='field' />
          <folder-item name='[WorkStation Area]' type='field' />
          <folder-item name='[WorkStation Channel]' type='field' />
        </folder>
        <folder layered='true' name='10 - Promotion'>
          <folder-item name='[OMNI Promotion Code]' type='field' />
          <folder-item name='[OMNI Promotion Name]' type='field' />
          <folder-item name='[Promotion Classification]' type='field' />
          <folder-item name='[Promotion DMG Description]' type='field' />
          <folder-item name='[Promotion DMG]' type='field' />
          <folder-item name='[Promotion Flag]' type='field' />
          <folder-item name='[Promotion ID]' type='field' />
          <folder-item name='[Promotion Type]' type='field' />
          <folder-item name='[Promotion Valid From]' type='field' />
          <folder-item name='[Promotion Valid To]' type='field' />
        </folder>
        <folder layered='true' name='11 - Attendance'>
          <folder-item name='[Gate Siteid]' type='field' />
          <folder-item name='[Scan Action]' type='field' />
        </folder>
        <folder layered='true' name='11 - Guest Information'>
          <folder-item name='[Account AK]' type='field' />
          <folder-item name='[Address]' type='field' />
          <folder-item name='[City]' type='field' />
          <folder-item name='[Country of Residence New]' type='field' />
          <folder-item name='[Country of Residence ]' type='field' />
          <folder-item name='[Customer Segment]' type='field' />
          <folder-item name='[Customer Type]' type='field' />
          <folder-item name='[EH Client Country Name]' type='field' />
          <folder-item name='[Email ]' type='field' />
          <folder-item name='[Emirate State]' type='field' />
          <folder-item name='[Etihad ID]' type='field' />
          <folder-item name='[Farah Staff Flag]' type='field' />
          <folder-item name='[Fax Number]' type='field' />
          <folder-item name='[First Name]' type='field' />
          <folder-item name='[Gender]' type='field' />
          <folder-item name='[Guest Type]' type='field' />
          <folder-item name='[Industry]' type='field' />
          <folder-item name='[Language]' type='field' />
          <folder-item name='[Last Name]' type='field' />
          <folder-item name='[Local/Distant]' type='field' />
          <folder-item name='[MDM ID]' type='field' />
          <folder-item name='[Marital Status]' type='field' />
          <folder-item name='[Middle Name]' type='field' />
          <folder-item name='[Miral Staff Flag]' type='field' />
          <folder-item name='[Miral Staff ID]' type='field' />
          <folder-item name='[Mobile Number]' type='field' />
          <folder-item name='[Nationality New]' type='field' />
          <folder-item name='[Nationality ]' type='field' />
          <folder-item name='[Occupation]' type='field' />
          <folder-item name='[Oracle Account ID]' type='field' />
          <folder-item name='[P O Box]' type='field' />
          <folder-item name='[Parent Partner CRM Account ID]' type='field' />
          <folder-item name='[Parent Partner CRM Account Name]' type='field' />
          <folder-item name='[SCV ID]' type='field' />
          <folder-item name='[Title]' type='field' />
          <folder-item name='[YAS ID]' type='field' />
          <folder-item name='[Zip Pincode]' type='field' />
        </folder>
        <folder layered='true' name='12 - Partner Information'>
          <folder-item name='[B2B Account ID]' type='field' />
          <folder-item name='[EH Client Region Name]' type='field' />
          <folder-item name='[EH DMC Flag]' type='field' />
          <folder-item name='[OMNI Account Category DMG Recursive Name]' type='field' />
          <folder-item name='[OMNI Account Category/DMG Code]' type='field' />
          <folder-item name='[OMNI Account Category/DMG Name]' type='field' />
          <folder-item name='[OMNI Account Company Name]' type='field' />
          <folder-item name='[OMNI Account Email]' type='field' />
          <folder-item name='[OMNI Account ID]' type='field' />
          <folder-item name='[OMNI Account Name]' type='field' />
          <folder-item name='[OMNI Account Phone No.]' type='field' />
          <folder-item name='[OMNI Multipark y/n]' type='field' />
          <folder-item name='[OMNI Park Combination]' type='field' />
          <folder-item name='[Partner Account DMG Code (OMNI) (group)]' type='field' />
          <folder-item name='[Partner Account DMG Code (OMNI)]' type='field' />
          <folder-item name='[Partner Account DMG Description (OMNI)]' type='field' />
          <folder-item name='[Partner Company Account Id (OMNI)]' type='field' />
          <folder-item name='[Partner Company Account Name (OMNI)]' type='field' />
        </folder>
        <folder layered='true' name='12.1 - CRM'>
          <folder-item name='[CRM Account DMG Code]' type='field' />
          <folder-item name='[CRM Account DMG Name]' type='field' />
          <folder-item name='[CRM Account Email]' type='field' />
          <folder-item name='[CRM Account ID]' type='field' />
          <folder-item name='[CRM Account Name]' type='field' />
          <folder-item name='[CRM Account Phone No.]' type='field' />
          <folder-item name='[CRM Account SubDMG Code]' type='field' />
          <folder-item name='[CRM Account SubDMG Name]' type='field' />
        </folder>
        <folder layered='true' name='12.2 - Agent'>
          <folder-item name='[Agent CRM Email]' type='field' />
          <folder-item name='[Agent CRM ID]' type='field' />
          <folder-item name='[Agent CRM Name]' type='field' />
          <folder-item name='[Agent CRM Phone No.]' type='field' />
          <folder-item name='[Agent OMNI Account Email]' type='field' />
          <folder-item name='[Agent OMNI Account ID]' type='field' />
          <folder-item name='[Agent OMNI Account Name]' type='field' />
          <folder-item name='[Agent OMNI Account Phone No.]' type='field' />
          <folder-item name='[Agent Oracle Account ID]' type='field' />
          <folder-item name='[Agent TravelBox Account Email]' type='field' />
          <folder-item name='[Agent TravelBox Account ID]' type='field' />
          <folder-item name='[Agent TravelBox Account Name]' type='field' />
          <folder-item name='[Agent TravelBox Account Phone No.]' type='field' />
          <folder-item name='[Agent Yas Arena Account Email]' type='field' />
          <folder-item name='[Agent Yas Arena Account ID]' type='field' />
          <folder-item name='[Agent Yas Arena Account Name]' type='field' />
          <folder-item name='[Agent Yas Arena Account Phone No.]' type='field' />
        </folder>
        <folder layered='true' name='12.3 TravelBox'>
          <folder-item name='[TravelBox Account Category/DMG Code]' type='field' />
          <folder-item name='[TravelBox Account Category/DMG Name]' type='field' />
          <folder-item name='[TravelBox Account Email]' type='field' />
          <folder-item name='[TravelBox Account ID]' type='field' />
          <folder-item name='[TravelBox Account Name]' type='field' />
          <folder-item name='[TravelBox Account Phone No.]' type='field' />
        </folder>
        <folder layered='true' name='12.4 Yas Arena'>
          <folder-item name='[Yas Arena Account Category/DMG Code]' type='field' />
          <folder-item name='[Yas Arena Account Category/DMG Name]' type='field' />
          <folder-item name='[Yas Arena Account Email]' type='field' />
          <folder-item name='[Yas Arena Account ID]' type='field' />
          <folder-item name='[Yas Arena Account Name]' type='field' />
          <folder-item name='[Yas Arena Account Phone No.]' type='field' />
        </folder>
        <folder layered='true' name='13 - Vouchers'>
          <folder-item name='[Voucher Code]' type='field' />
          <folder-item name='[Voucher Company Name]' type='field' />
          <folder-item name='[Voucher DMG Category Code]' type='field' />
          <folder-item name='[Voucher DMG Category Name]' type='field' />
          <folder-item name='[Voucher Name]' type='field' />
        </folder>
        <folder layered='true' name='14 - Source'>
          <folder-item name='[Source Name]' type='field' />
        </folder>
        <folder layered='true' name='15 - Partner Discount'>
          <folder-item name='[Card Type]' type='field' />
          <folder-item name='[Partner Discount Card Number]' type='field' />
          <folder-item name='[Partner Discount Expiry Date]' type='field' />
          <folder-item name='[Partner Discount Registration Channel]' type='field' />
        </folder>
        <folder layered='true' name='Measures 01 - Attendance'>
          <folder-item name='[Attendance_Count]' type='field' />
          <folder-item name='[Budget Attendance]' type='field' />
          <folder-item name='[Calculation_2183682895431348224]' type='field' />
          <folder-item name='[Forecast Attendance]' type='field' />
          <folder-item name='[Forecast Label]' type='field' />
        </folder>
      </folders-common>
      <layout dim-ordering='alphabetic' measure-ordering='alphabetic' show-hidden-fields='true' show-structure='false' />
      <semantic-values>
        <semantic-value key='[Country].[Name]' value='&quot;United States&quot;' />
      </semantic-values>
      <object-graph>
        <objects>
          <object caption='Migrated Data' id='Migrated Data'>
            <properties context=''>
              <relation name='sqlproxy' table='[sqlproxy]' type='table' />
            </properties>
          </object>
        </objects>
      </object-graph>
    </datasource>
  </datasources>
  <datasource-relationships>
    <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
      <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
        <aliases>
          <alias key='%null%' value='CLYMB' />
        </aliases>
      </column>
      <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
      <column-instance column='[SUBMIT_DATE]' derivation='Day' name='[dy:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Day-Trunc' name='[tdy:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Month-Trunc' name='[tmn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Year-Trunc' name='[tyr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
      <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
    </datasource-dependencies>
    <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
      <column aggregation='Year' datatype='date' default-type='ordinal' layered='true' name='[Attendance Date]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
      <column aggregation='Count' caption='Ticket Use Facility' datatype='string' default-type='nominal' layered='true' name='[Redemption Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
      <column-instance column='[Attendance Date]' derivation='Day' name='[dy:Attendance Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Attendance Date]' derivation='Month' name='[mn:Attendance Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Redemption Company Name]' derivation='None' name='[none:Redemption Company Name:nk]' pivot='key' type='nominal' />
      <column-instance column='[Attendance Date]' derivation='Day-Trunc' name='[tdy:Attendance Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Attendance Date]' derivation='Month-Trunc' name='[tmn:Attendance Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Attendance Date]' derivation='Year-Trunc' name='[tyr:Attendance Date:ok]' pivot='key' type='ordinal' />
      <column-instance column='[Attendance Date]' derivation='Year' name='[yr:Attendance Date:ok]' pivot='key' type='ordinal' />
    </datasource-dependencies>
    <datasource-relationship source='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' target='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
      <column-mapping>
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[dy:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[dy:SUBMIT_DATE:ok]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[mn:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[none:Redemption Company Name:nk]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[tdy:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tdy:SUBMIT_DATE:ok]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[tmn:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:ok]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[tyr:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tyr:SUBMIT_DATE:ok]' />
        <map key='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[yr:Attendance Date:ok]' value='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' />
      </column-mapping>
    </datasource-relationship>
  </datasource-relationships>
  <worksheets>
    <worksheet name='Attendance check'>
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='Year' caption='As of Date' datatype='date' default-type='ordinal' layered='true' name='[Calculation_732679402495188995]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default'>
              <calculation class='tableau' formula='date([SUBMIT_DATE])&#13;&#10;&#13;&#10;&#13;&#10;//DATE(left(str([DATE_KEY]),4)+&quot;-&quot;+mid(str([DATE_KEY]),5,2)+&quot;-&quot;+mid(str([DATE_KEY]),7,2))' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Calculation_732679402495188995]' derivation='None' name='[none:Calculation_732679402495188995:qk]' pivot='key' type='quantitative' />
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Year' datatype='date' default-type='ordinal' layered='true' name='[Attendance Date]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
            <column aggregation='Count' caption='Ticket Use Facility' datatype='string' default-type='nominal' layered='true' name='[Redemption Company Name]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
            <column-instance column='[Attendance_Count]' derivation='Sum' name='[sum:Attendance_Count:qk]' pivot='key' type='quantitative' />
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='quantitative' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_732679402495188995:qk]' included-values='in-range'>
            <min>#2019-01-01#</min>
            <max>#2022-08-30#</max>
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_732679402495188995:qk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='header'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' value='172' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='136' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[sum:Attendance_Count:qk]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok])</rows>
        <cols />
        <join-lod-include-overrides>
          <column>[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance Date]</column>
          <column>[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Redemption Company Name]</column>
        </join-lod-include-overrides>
      </table>
      <simple-id uuid='{7E024F92-16D6-4FC9-8DB3-CAB4F2DBDEE5}' />
    </worksheet>
    <worksheet name='COR Grouped by month'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/workbooks/DemographicsMonthly/CORGroupedbymonth?rev=' id='5962012' path='/t/miralexperiences/workbooks/DemographicsMonthly' revision='' site='miralexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' layered='true' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='CoR Grouped' datatype='string' name='[China Country (copy)_548031817853374469]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[China Country (copy)_548031817853374469]' derivation='None' name='[none:China Country (copy)_548031817853374469:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:2]' pivot='key' type='quantitative'>
              <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' ordering-type='Field' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' ordering-type='Field' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;United Arab Emirates&quot;</bucket>
              <bucket>&quot;GCC&quot;</bucket>
              <bucket>&quot;China&quot;</bucket>
              <bucket>&quot;Russia&quot;</bucket>
              <bucket>&quot;United Kingdom&quot;</bucket>
              <bucket>&quot;Germany&quot;</bucket>
              <bucket>&quot;India&quot;</bucket>
              <bucket>&quot;United States&quot;</bucket>
              <bucket>&quot;France&quot;</bucket>
              <bucket>&quot;RoW&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='99' />
          </style-rule>
          <style-rule element='header'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='44' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='108' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' value='168' />
          </style-rule>
          <style-rule element='label'>
            <format attr='text-format' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='iLLL' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:2]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]))</cols>
      </table>
      <simple-id uuid='{5CB58840-D317-45E2-AB41-EBE2030C38BF}' />
    </worksheet>
    <worksheet name='Nationality (Top 20)'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/farahexperiences/workbooks/DemographicsWorkings/NationalityTop20?rev=' id='3370404' path='/t/farahexperiences/workbooks/DemographicsWorkings' revision='' site='farahexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource name='Parameters' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='Parameters'>
            <column caption='P1 - To Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[P1 - From Date (copy)]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-31#'>
              <calculation class='tableau' formula='#2019-01-31#' />
            </column>
            <column caption='Top N' datatype='integer' name='[Parameter 1]' param-domain-type='any' role='measure' type='quantitative' value='20'>
              <calculation class='tableau' formula='20' />
            </column>
            <column caption='P1 - From Date' datatype='date' default-format='*dddd, mmmm d, yyyy' name='[Parameter 2]' param-domain-type='any' role='measure' type='quantitative' value='#2019-01-01#'>
              <calculation class='tableau' formula='#2019-01-01#' />
            </column>
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='Year' caption='As of Date' datatype='date' default-type='ordinal' layered='true' name='[Calculation_732679402495188995]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default'>
              <calculation class='tableau' formula='date([SUBMIT_DATE])&#13;&#10;&#13;&#10;&#13;&#10;//DATE(left(str([DATE_KEY]),4)+&quot;-&quot;+mid(str([DATE_KEY]),5,2)+&quot;-&quot;+mid(str([DATE_KEY]),7,2))' />
            </column>
            <column aggregation='Sum' caption='P1 Records ' datatype='integer' default-type='quantitative' layered='true' name='[Calculation_732679402505031690]' pivot='key' role='measure' type='quantitative' user-datatype='integer' visual-totals='Default'>
              <calculation class='tableau' formula='if [Calculation_732679402495188995]&gt;= [Parameters].[Parameter 2] and [Calculation_732679402495188995]&lt;= [Parameters].[P1 - From Date (copy)]&#13;&#10;then [Number of Records] END' />
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='Count' caption='Country of Nationality Group' datatype='string' default-type='nominal' layered='true' name='[Calculation_851180334268956681]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <calculation class='tableau' formula='IF  [Top 20 Country of Nationality]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' layered='true' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Day' name='[dy:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[Top 20 Country of Nationality]' derivation='InOut' name='[io:Top 20 Country of Nationality:nk]' pivot='key' type='nominal' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Calculation_851180334268956681]' derivation='None' name='[none:Calculation_851180334268956681:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:13]' pivot='key' type='quantitative'>
              <table-calc ordering-type='Columns' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Columns' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Year' datatype='date' default-type='ordinal' layered='true' name='[Attendance Date]' pivot='key' role='dimension' type='ordinal' user-datatype='date' visual-totals='Default' />
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]' kind='hide'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-manual-selection='true' user:ui-manual-selection-all-when-empty='true' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[io:Top 20 Country of Nationality:nk]' />
              <groupfilter function='member' level='[io:Top 20 Country of Nationality:nk]' member='false' />
            </groupfilter>
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='member' level='[none:COMPANY_NAME:nk]' member='&quot;Ferrari World Abu Dhabi&quot;' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' direction='ASC'>
            <dictionary>
              <bucket>%all%</bucket>
              <bucket>&quot;United Arab Emirates&quot;</bucket>
              <bucket>&quot;United Kingdom&quot;</bucket>
              <bucket>&quot;Other&quot;</bucket>
              <bucket>&quot;India&quot;</bucket>
              <bucket>&quot;United States&quot;</bucket>
              <bucket>&quot;Egypt&quot;</bucket>
              <bucket>&quot;Philippines&quot;</bucket>
              <bucket>&quot;Jordan&quot;</bucket>
              <bucket>&quot;Lebanon&quot;</bucket>
              <bucket>&quot;France&quot;</bucket>
              <bucket>&quot;Australia&quot;</bucket>
              <bucket>&quot;South Africa&quot;</bucket>
              <bucket>&quot;Palestine&quot;</bucket>
              <bucket>&quot;Germany&quot;</bucket>
              <bucket>&quot;Syria&quot;</bucket>
              <bucket>&quot;Canada&quot;</bucket>
              <bucket>&quot;Russia&quot;</bucket>
              <bucket>&quot;Pakistan&quot;</bucket>
              <bucket>&quot;Brazil&quot;</bucket>
              <bucket>&quot;China&quot;</bucket>
              <bucket>&quot;Italy&quot;</bucket>
              <bucket>&quot;Spain&quot;</bucket>
              <bucket>&quot;Iran&quot;</bucket>
              <bucket>&quot;Kazakhstan&quot;</bucket>
              <bucket>&quot;Colombia&quot;</bucket>
              <bucket>&quot;Burma&quot;</bucket>
              <bucket>&quot;Bahrain&quot;</bucket>
              <bucket>&quot;Ukraine&quot;</bucket>
              <bucket>&quot;Saudi Arabia&quot;</bucket>
              <bucket>&quot;Mexico&quot;</bucket>
              <bucket>&quot;Kuwait&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='header'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk]' value='132' />
          </style-rule>
          <style-rule element='label'>
            <format attr='display' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]' value='false' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:13]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_851180334268956681:nk])</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[dy:SUBMIT_DATE:ok])))</cols>
        <join-lod-include-overrides>
          <column>[sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance Date]</column>
        </join-lod-include-overrides>
      </table>
      <simple-id uuid='{F0D67156-F2DD-402C-97B0-84BB17ACEB73}' />
    </worksheet>
    <worksheet name='Nationality (individual filter)'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/farahexperiences/workbooks/DemographicsWorkings/Nationalityindividualfilter?rev=' id='3370403' path='/t/farahexperiences/workbooks/DemographicsWorkings' revision='' site='farahexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource name='Parameters' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='Parameters'>
            <column caption='Country of Nationality Parameter' datatype='string' name='[Country of Nationality Parameter]' param-domain-type='list' role='measure' type='nominal' value='&quot;United Arab Emirates&quot;'>
              <calculation class='tableau' formula='&quot;United Arab Emirates&quot;' />
            </column>
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='Country of Nationality Group (New)' datatype='string' name='[Country of Nationality Group (copy)_1558808454741692424]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF  [Parameters].[Country of Nationality Parameter]=[NATIONALITY]&#13;&#10;THEN [NATIONALITY] ELSE &quot;Other&quot; END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' layered='true' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Day' name='[dy:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Country of Nationality Group (copy)_1558808454741692424]' derivation='None' name='[none:Country of Nationality Group (copy)_1558808454741692424:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:119]' pivot='key' type='quantitative'>
              <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country of Nationality Group (copy)_1558808454741692424]' ordering-type='Field' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country of Nationality Group (copy)_1558808454741692424]' ordering-type='Field' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' context='true'>
            <groupfilter function='member' level='[none:COMPANY_NAME:nk]' member='&quot;Ferrari World Abu Dhabi&quot;' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Nationality Group (copy)_1558808454741692424:nk]' kind='hide'>
            <groupfilter function='except' user:ui-domain='relevant' user:ui-enumeration='exclusive' user:ui-manual-selection='true' user:ui-manual-selection-all-when-empty='true' user:ui-marker='enumerate'>
              <groupfilter function='level-members' level='[none:Country of Nationality Group (copy)_1558808454741692424:nk]' />
              <groupfilter function='member' level='[none:Country of Nationality Group (copy)_1558808454741692424:nk]' member='&quot;Other&quot;' />
            </groupfilter>
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Nationality Group (copy)_1558808454741692424:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;United Arab Emirates&quot;</bucket>
              <bucket>&quot;Other&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style />
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:119]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Nationality Group (copy)_1558808454741692424:nk] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[dy:SUBMIT_DATE:ok])</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]))</cols>
      </table>
      <simple-id uuid='{3728BE91-556C-4D59-AF1C-9A03FDD364B1}' />
    </worksheet>
    <worksheet name='Nationality Grouped by Month'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/workbooks/DemographicsMonthly/NationalityGroupedbyMonth?rev=' id='10209367' path='/t/miralexperiences/workbooks/DemographicsMonthly' revision='' site='miralexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='Nationality Grouped' datatype='string' name='[Country Grouped (copy)_756323266502594583]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [NATIONALITY]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' layered='true' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Country Grouped (copy)_756323266502594583]' derivation='None' name='[none:Country Grouped (copy)_756323266502594583:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:38]' pivot='key' type='quantitative'>
              <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]' value='30' />
          </style-rule>
          <style-rule element='header'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]' value='124' />
          </style-rule>
          <style-rule element='label'>
            <format attr='text-format' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='iLLL' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:38]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minheight' value='-1' />
                <format attr='maxheight' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]))</cols>
      </table>
      <simple-id uuid='{FF046C5F-2432-4BDC-AB78-B2ADFB321387}' />
    </worksheet>
    <worksheet name='Nationality Grouped by Month (new)'>
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='Nationality Grouped' datatype='string' name='[Country Grouped (copy)_756323266502594583]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [NATIONALITY]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [NATIONALITY]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='None' caption='Nationality' datatype='string' default-type='nominal' layered='true' name='[NATIONALITY]' pivot='key' role='dimension' semantic-role='[County].[Name]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Country Grouped (copy)_756323266502594583]' derivation='None' name='[none:Country Grouped (copy)_756323266502594583:nk]' pivot='key' type='nominal' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month-Trunc' name='[tmn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month-Trunc' name='[tmn:SUBMIT_DATE:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:38]' pivot='key' type='quantitative'>
              <table-calc ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Country Grouped (copy)_756323266502594583]' ordering-type='Field' />
            </column-instance>
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='quantitative' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:qk]' context='true' included-values='in-range'>
            <min>#2024-01-01 00:00:00#</min>
            <max>#2024-07-01 00:00:00#</max>
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:qk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]' value='30' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:ok]' value='97' />
          </style-rule>
          <style-rule element='header'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]' value='124' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:38]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minheight' value='-1' />
                <format attr='maxheight' value='-1' />
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:ok])</cols>
      </table>
      <simple-id uuid='{6EF4922F-6FE6-4FAC-AD00-75B0C7AF6AFC}' />
    </worksheet>
    <worksheet name='Number of responses check'>
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' layered='true' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column caption='Submit Dt' datatype='date' name='[Calculation_756323266478395409]' role='dimension' type='ordinal'>
              <calculation class='tableau' formula='DATE([SUBMIT_DATE])' />
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='CoR Grouped' datatype='string' name='[China Country (copy)_548031817853374469]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;United Arab Emirates&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;China&quot; THEN &quot;China&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Russia&quot; THEN &quot;Russia&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United Kingdom&quot; THEN &quot;United Kingdom&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Germany&quot; THEN &quot;Germany&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;India&quot; THEN &quot;India&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;United States&quot; THEN &quot;United States&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;France&quot; THEN &quot;France&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Saudi Arabia&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Bahrain&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Kuwait&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Oman&quot; THEN &quot;GCC&quot;&#13;&#10;ELSEIF [COUNTRY_OF_RESIDENCE]=&quot;Qatar&quot; THEN &quot;GCC&quot;&#13;&#10;ELSE &quot;RoW&quot;&#13;&#10;END' />
            </column>
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[Calculation_756323266478395409]' derivation='Month' name='[mn:Calculation_756323266478395409:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Calculation_756323266478395409]' derivation='None' name='[none:Calculation_756323266478395409:qk]' pivot='key' type='quantitative' />
            <column-instance column='[China Country (copy)_548031817853374469]' derivation='None' name='[none:China Country (copy)_548031817853374469:nk]' pivot='key' type='nominal' />
            <column-instance column='[Number of Records]' derivation='Sum' name='[sum:Number of Records:qk]' pivot='key' type='quantitative' />
            <column-instance column='[Calculation_851180334257242114]' derivation='User' name='[usr:Calculation_851180334257242114:qk:20]' pivot='key' type='quantitative'>
              <table-calc ordering-type='Field'>
                <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[COMPANY_NAME]' />
                <order field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[China Country (copy)_548031817853374469]' />
              </table-calc>
            </column-instance>
            <column-instance column='[Calculation_756323266478395409]' derivation='Year' name='[yr:Calculation_756323266478395409:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[:Measure Names]'>
            <groupfilter function='union' user:op='manual'>
              <groupfilter function='member' level='[:Measure Names]' member='&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[sum:Number of Records:qk]&quot;' />
              <groupfilter function='member' level='[:Measure Names]' member='&quot;[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Calculation_851180334257242114:qk:20]&quot;' />
            </groupfilter>
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='member' level='[none:COMPANY_NAME:nk]' member='&quot;Ferrari World Abu Dhabi&quot;' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <filter class='quantitative' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_756323266478395409:qk]' included-values='in-range'>
            <min>#2019-01-01#</min>
            <max>#2022-08-30#</max>
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;United Arab Emirates&quot;</bucket>
              <bucket>&quot;GCC&quot;</bucket>
              <bucket>&quot;China&quot;</bucket>
              <bucket>&quot;France&quot;</bucket>
              <bucket>&quot;Germany&quot;</bucket>
              <bucket>&quot;India&quot;</bucket>
              <bucket>&quot;Russia&quot;</bucket>
              <bucket>&quot;United Kingdom&quot;</bucket>
              <bucket>&quot;United States&quot;</bucket>
              <bucket>&quot;RoW&quot;</bucket>
            </dictionary>
          </manual-sort>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_756323266478395409:qk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[:Measure Names]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='57' />
          </style-rule>
          <style-rule element='header'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[:Measure Names]' value='88' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Multiple Values]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minheight' value='-1' />
                <format attr='maxheight' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[:Measure Names] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]))</rows>
        <cols>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:Calculation_756323266478395409:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:Calculation_756323266478395409:ok])</cols>
      </table>
      <simple-id uuid='{FC937CD0-CEFD-4C33-82A2-F9182B3C0467}' />
    </worksheet>
    <worksheet name='Residents by Emirates  Grouped by month'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/workbooks/DemographicsMonthly/ResidentsbyEmiratesGroupedbymonth?rev=' id='5962014' path='/t/miralexperiences/workbooks/DemographicsMonthly' revision='' site='miralexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' layered='true' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column caption='Tourist/Residents' datatype='string' name='[Calculation_1133781257396064256]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;Residents&quot;&#13;&#10;ELSE &quot;Tourist&quot;&#13;&#10;END' />
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='Count' caption='Emirate' datatype='string' default-type='nominal' layered='true' name='[EMIRATE_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default' />
            <column caption='Emirate Grouped' datatype='string' name='[Emirate (copy)_756323266501898260]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='if [EMIRATE_NAME]=&quot;Abu Dhabi&quot; THEN &quot;Abu Dhabi&quot;&#13;&#10;ELSEIF [EMIRATE_NAME]=&quot;Dubai&quot; THEN &quot;Dubai&quot;&#13;&#10;else &quot;Other Emirates&quot;&#13;&#10;END' />
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Calculation_1133781257396064256]' derivation='None' name='[none:Calculation_1133781257396064256:nk]' pivot='key' type='nominal' />
            <column-instance column='[Emirate (copy)_756323266501898260]' derivation='None' name='[none:Emirate (copy)_756323266501898260:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:13]' pivot='key' type='quantitative'>
              <table-calc ordering-type='Columns' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Columns' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' context='true'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='99' />
          </style-rule>
          <style-rule element='header'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='44' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='108' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Emirate (copy)_756323266501898260:nk]' value='120' />
          </style-rule>
          <style-rule element='label'>
            <format attr='text-format' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='iLLL' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:13]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_1133781257396064256:nk] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Emirate (copy)_756323266501898260:nk])</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]))</cols>
      </table>
      <simple-id uuid='{0DCD39DE-4B00-401A-8DAE-60E88F5DE769}' />
    </worksheet>
    <worksheet name='Tourist/Residents  Grouped by month'>
      <repository-location derived-from='https://eu-west-1a.online.tableau.com/t/miralexperiences/workbooks/DemographicsMonthly/TouristResidentsGroupedbymonth?rev=' id='5962013' path='/t/miralexperiences/workbooks/DemographicsMonthly' revision='' site='miralexperiences' />
      <table>
        <view>
          <datasources>
            <datasource caption='Demographics Dataset' name='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek' />
            <datasource caption='Attendance SS' name='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd' />
          </datasources>
          <datasource-dependencies datasource='sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek'>
            <column aggregation='Count' caption='Facility Name' datatype='string' default-type='nominal' layered='true' name='[COMPANY_NAME]' pivot='key' role='dimension' type='nominal' user-datatype='string' visual-totals='Default'>
              <aliases>
                <alias key='%null%' value='CLYMB' />
              </aliases>
            </column>
            <column aggregation='None' caption='Country of Residence' datatype='string' default-type='nominal' layered='true' name='[COUNTRY_OF_RESIDENCE]' pivot='key' role='dimension' semantic-role='[Country].[ISO3166_2]' type='nominal' user-datatype='string' visual-totals='Default' />
            <column caption='Tourist/Residents' datatype='string' name='[Calculation_1133781257396064256]' role='dimension' type='nominal'>
              <calculation class='tableau' formula='IF [COUNTRY_OF_RESIDENCE]=&quot;United Arab Emirates&quot; THEN &quot;Residents&quot;&#13;&#10;ELSE &quot;Tourist&quot;&#13;&#10;END' />
            </column>
            <column caption='Percentage of Sample' datatype='real' default-format='p0.00%' name='[Calculation_851180334257242114]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='sum([Number of Records])/Total(SUM([Number of Records]))'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column caption='Estimated Attendance' datatype='real' name='[Estimated Attendance (copy)]' role='measure' type='quantitative'>
              <calculation class='tableau' formula='SUM([sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd].[Attendance_Count])*[Calculation_851180334257242114]'>
                <table-calc ordering-type='Rows' />
              </calculation>
            </column>
            <column aggregation='Sum' datatype='integer' default-type='quantitative' layered='true' name='[Number of Records]' pivot='key' role='measure' type='quantitative' user-datatype='integer' user:auto-column='numrec' visual-totals='Default'>
              <calculation class='tableau' formula='1' />
            </column>
            <column aggregation='Year' caption='Submit_Date' datatype='datetime' default-type='ordinal' layered='true' name='[SUBMIT_DATE]' pivot='key' role='dimension' type='ordinal' user-datatype='datetime' visual-totals='Default' />
            <column-instance column='[SUBMIT_DATE]' derivation='Month' name='[mn:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
            <column-instance column='[COMPANY_NAME]' derivation='None' name='[none:COMPANY_NAME:nk]' pivot='key' type='nominal' />
            <column-instance column='[Calculation_1133781257396064256]' derivation='None' name='[none:Calculation_1133781257396064256:nk]' pivot='key' type='nominal' />
            <column-instance column='[Estimated Attendance (copy)]' derivation='User' name='[usr:Estimated Attendance (copy):qk:13]' pivot='key' type='quantitative'>
              <table-calc ordering-type='Columns' />
              <table-calc field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[Calculation_851180334257242114]' ordering-type='Columns' />
            </column-instance>
            <column-instance column='[SUBMIT_DATE]' derivation='Year' name='[yr:SUBMIT_DATE:ok]' pivot='key' type='ordinal' />
          </datasource-dependencies>
          <datasource-dependencies datasource='sqlproxy.09kt3vy1w9bbou1fm6bzy1i4wotd'>
            <column aggregation='Sum' datatype='real' default-type='quantitative' layered='true' name='[Attendance_Count]' pivot='key' role='measure' type='quantitative' user-datatype='real' visual-totals='Default'>
              <desc>
                <formatted-text>
                  <run fontname='Tableau Medium' fontsize='8'>

To be used for CLYMB only                </run>
                </formatted-text>
              </desc>
            </column>
          </datasource-dependencies>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' context='true' filter-group='6'>
            <groupfilter function='level-members' level='[mn:SUBMIT_DATE:ok]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]'>
            <groupfilter function='level-members' level='[none:COMPANY_NAME:nk]' user:ui-enumeration='all' user:ui-marker='enumerate' />
          </filter>
          <manual-sort column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' direction='ASC'>
            <dictionary>
              <bucket>&quot;Ferrari World Abu Dhabi&quot;</bucket>
              <bucket>&quot;Yas Waterworld&quot;</bucket>
              <bucket>&quot;Warner Bros&quot;</bucket>
              <bucket>&quot;Clymb Entertainment&quot;</bucket>
            </dictionary>
          </manual-sort>
          <filter class='categorical' column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' context='true' filter-group='5'>
            <groupfilter function='member' level='[yr:SUBMIT_DATE:ok]' member='2024' user:ui-domain='relevant' user:ui-enumeration='inclusive' user:ui-marker='enumerate' />
          </filter>
          <slices>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</column>
            <column>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</column>
          </slices>
          <aggregation value='true' />
        </view>
        <style>
          <style-rule element='cell'>
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='99' />
          </style-rule>
          <style-rule element='header'>
            <format attr='height' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='44' />
            <format attr='width' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' value='108' />
          </style-rule>
          <style-rule element='label'>
            <format attr='text-format' field='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' value='iLLL' />
          </style-rule>
        </style>
        <panes>
          <pane selection-relaxation-option='selection-relaxation-allow'>
            <view>
              <breakdown value='auto' />
            </view>
            <mark class='Automatic' />
            <encodings>
              <text column='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[usr:Estimated Attendance (copy):qk:13]' />
            </encodings>
            <style>
              <style-rule element='mark'>
                <format attr='mark-labels-show' value='true' />
              </style-rule>
              <style-rule element='pane'>
                <format attr='minwidth' value='-1' />
                <format attr='maxwidth' value='-1' />
              </style-rule>
            </style>
          </pane>
        </panes>
        <rows total='true'>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_1133781257396064256:nk]</rows>
        <cols total='true'>([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok] / ([sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok] / [sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]))</cols>
      </table>
      <simple-id uuid='{D45ABBEB-E16D-4347-8706-71FD69EA787B}' />
    </worksheet>
  </worksheets>
  <windows source-height='58'>
    <window class='worksheet' name='Nationality (individual filter)'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' type='filter' />
            <card mode='dropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' type='filter' />
            <card mode='compact' param='[Parameters].[Country of Nationality Parameter]' type='parameter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{967ECF92-B913-478F-8977-CFAD0D298219}' />
    </window>
    <window class='worksheet' name='Nationality (Top 20)'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='dropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{394C3416-8136-4528-820C-EA48C3373EE1}' />
    </window>
    <window class='worksheet' name='COR Grouped by month' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='192'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' show-apply='true' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{9C664E40-9AB7-4544-AAE1-85B4CCC37299}' />
    </window>
    <window class='worksheet' name='Tourist/Residents  Grouped by month' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='192'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{577D7B58-8E31-4769-B2B6-F4CC35B372A2}' />
    </window>
    <window class='worksheet' name='Residents by Emirates  Grouped by month' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='192'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{22C1D8AC-73FA-45FB-AB22-E449F1CBD384}' />
    </window>
    <window class='worksheet' maximized='true' name='Nationality Grouped by Month' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]' show-apply='true' type='filter' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:SUBMIT_DATE:ok]' show-apply='true' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{00033841-BD64-4717-899A-347E2577CD45}' />
    </window>
    <window class='worksheet' name='Nationality Grouped by Month (new)' tab-color='#17927d'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='160'>
            <card param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[tmn:SUBMIT_DATE:qk]' show-domain='false' show-null-ctrls='false' type='filter' values='relevant' />
            <card mode='checkdropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' show-apply='true' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[io:Top 20 Country of Nationality:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country Grouped (copy)_756323266502594583:nk]</field>
          </color-one-way>
        </highlight>
        <default-map-tool-selection tool='2' />
      </viewpoint>
      <simple-id uuid='{24854DF7-2195-421A-9FA9-E36401D2B394}' />
    </window>
    <window class='worksheet' name='Attendance check'>
      <cards>
        <edge name='left'>
          <strip size='300'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='31'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='266'>
            <card mode='dropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' size='27' type='filter' />
            <card param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_732679402495188995:qk]' show-domain='false' show-null-ctrls='false' size='44' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_732679402495188995:qk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:Calculation_732679402495188995:ok]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:SUBMIT_DATE:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{139CE320-091E-41EF-8307-6977BB99181E}' />
    </window>
    <window class='worksheet' name='Number of responses check'>
      <cards>
        <edge name='left'>
          <strip size='268'>
            <card type='pages' />
            <card type='filters' />
            <card type='marks' />
            <card type='measures' />
          </strip>
        </edge>
        <edge name='top'>
          <strip size='2147483647'>
            <card type='columns' />
          </strip>
          <strip size='2147483647'>
            <card type='rows' />
          </strip>
          <strip size='2147483647'>
            <card type='title' />
          </strip>
        </edge>
        <edge name='right'>
          <strip size='185'>
            <card param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_756323266478395409:qk]' show-domain='false' show-null-ctrls='false' type='filter' />
            <card mode='dropdown' param='[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]' type='filter' />
          </strip>
        </edge>
      </cards>
      <viewpoint>
        <highlight>
          <color-one-way>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[:Measure Names]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[mn:Calculation_756323266478395409:ok]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:COMPANY_NAME:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_490892395360825345:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Calculation_756323266478395409:qk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:China Country (copy)_548031817853374469:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[none:Country of Residence Group (copy)_756323266453856258:nk]</field>
            <field>[sqlproxy.07stu2m0sdjvwg1bwpj6t07yqtek].[yr:Calculation_756323266478395409:ok]</field>
          </color-one-way>
        </highlight>
      </viewpoint>
      <simple-id uuid='{3CE0DE01-6CD0-45F6-B2DE-F07CF5DF32B1}' />
    </window>
  </windows>
</workbook>

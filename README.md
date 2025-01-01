# Timezone Repository

This repository contains timezone data for various countries, including country codes, timezone identifiers, and GMT offsets. The data is structured in JSON format for easy use.

## Data Structure

The data is organized as a list of countries, each containing:

- **countryCode**: ISO 3166-1 alpha-2 country code.
- **countryName**: Full name of the country.

### Example JSON:

```json
{
    "timezones": [
      {
        "countryCode": "CI",
        "countryName": "Ivory Coast",
        "zoneName": "Africa/Abidjan",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "GH",
        "countryName": "Ghana",
        "zoneName": "Africa/Accra",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "ET",
        "countryName": "Ethiopia",
        "zoneName": "Africa/Addis_Ababa",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "DZ",
        "countryName": "Algeria",
        "zoneName": "Africa/Algiers",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "ER",
        "countryName": "Eritrea",
        "zoneName": "Africa/Asmara",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "ML",
        "countryName": "Mali",
        "zoneName": "Africa/Bamako",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "CF",
        "countryName": "Central African Republic",
        "zoneName": "Africa/Bangui",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "GM",
        "countryName": "Gambia",
        "zoneName": "Africa/Banjul",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "GW",
        "countryName": "Guinea-Bissau",
        "zoneName": "Africa/Bissau",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "MW",
        "countryName": "Malawi",
        "zoneName": "Africa/Blantyre",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "CG",
        "countryName": "Republic of the Congo",
        "zoneName": "Africa/Brazzaville",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "BI",
        "countryName": "Burundi",
        "zoneName": "Africa/Bujumbura",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "EG",
        "countryName": "Egypt",
        "zoneName": "Africa/Cairo",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "MA",
        "countryName": "Morocco",
        "zoneName": "Africa/Casablanca",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "ES",
        "countryName": "Spain",
        "zoneName": "Africa/Ceuta",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "GN",
        "countryName": "Guinea",
        "zoneName": "Africa/Conakry",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "SN",
        "countryName": "Senegal",
        "zoneName": "Africa/Dakar",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "TZ",
        "countryName": "Tanzania",
        "zoneName": "Africa/Dar_es_Salaam",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "DJ",
        "countryName": "Djibouti",
        "zoneName": "Africa/Djibouti",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "CM",
        "countryName": "Cameroon",
        "zoneName": "Africa/Douala",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MA",
        "countryName": "Morocco",
        "zoneName": "Africa/El_Aaiun",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "SL",
        "countryName": "Sierra Leone",
        "zoneName": "Africa/Freetown",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "BW",
        "countryName": "Botswana",
        "zoneName": "Africa/Gaborone",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "ZW",
        "countryName": "Zimbabwe",
        "zoneName": "Africa/Harare",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "ZA",
        "countryName": "South Africa",
        "zoneName": "Africa/Johannesburg",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "SS",
        "countryName": "South Sudan",
        "zoneName": "Africa/Juba",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "UG",
        "countryName": "Uganda",
        "zoneName": "Africa/Kampala",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "SD",
        "countryName": "Sudan",
        "zoneName": "Africa/Khartoum",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "RW",
        "countryName": "Rwanda",
        "zoneName": "Africa/Kigali",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "CD",
        "countryName": "Democratic Republic of the Congo",
        "zoneName": "Africa/Kinshasa",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "NG",
        "countryName": "Nigeria",
        "zoneName": "Africa/Lagos",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "GA",
        "countryName": "Gabon",
        "zoneName": "Africa/Libreville",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "TG",
        "countryName": "Togo",
        "zoneName": "Africa/Lome",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "AO",
        "countryName": "Angola",
        "zoneName": "Africa/Luanda",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "CD",
        "countryName": "Democratic Republic of the Congo",
        "zoneName": "Africa/Lubumbashi",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "ZM",
        "countryName": "Zambia",
        "zoneName": "Africa/Lusaka",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "GQ",
        "countryName": "Equatorial Guinea",
        "zoneName": "Africa/Malabo",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MZ",
        "countryName": "Mozambique",
        "zoneName": "Africa/Maputo",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "LS",
        "countryName": "Lesotho",
        "zoneName": "Africa/Maseru",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "SZ",
        "countryName": "Eswatini",
        "zoneName": "Africa/Mbabane",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "SO",
        "countryName": "Somalia",
        "zoneName": "Africa/Mogadishu",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "LR",
        "countryName": "Liberia",
        "zoneName": "Africa/Monrovia",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "KE",
        "countryName": "Kenya",
        "zoneName": "Africa/Nairobi",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "TD",
        "countryName": "Chad",
        "zoneName": "Africa/Ndjamena",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "NE",
        "countryName": "Niger",
        "zoneName": "Africa/Niamey",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MR",
        "countryName": "Mauritania",
        "zoneName": "Africa/Nouakchott",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "BF",
        "countryName": "Burkina Faso",
        "zoneName": "Africa/Ouagadougou",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "BJ",
        "countryName": "Benin",
        "zoneName": "Africa/Porto-Novo",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "ST",
        "countryName": "Sao Tome and Principe",
        "zoneName": "Africa/Sao_Tome",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "LY",
        "countryName": "Libya",
        "zoneName": "Africa/Tripoli",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "TN",
        "countryName": "Tunisia",
        "zoneName": "Africa/Tunis",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "NA",
        "countryName": "Namibia",
        "zoneName": "Africa/Windhoek",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Adak",
        "gmtOffset": -36000,
        "timestamp": 1735678078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Anchorage",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "AI",
        "countryName": "Anguilla",
        "zoneName": "America/Anguilla",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "AG",
        "countryName": "Antigua and Barbuda",
        "zoneName": "America/Antigua",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Araguaina",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Buenos_Aires",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Catamarca",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Cordoba",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Jujuy",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/La_Rioja",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Mendoza",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Rio_Gallegos",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Salta",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/San_Juan",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/San_Luis",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Tucuman",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AR",
        "countryName": "Argentina",
        "zoneName": "America/Argentina/Ushuaia",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AW",
        "countryName": "Aruba",
        "zoneName": "America/Aruba",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "PY",
        "countryName": "Paraguay",
        "zoneName": "America/Asuncion",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Atikokan",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Bahia",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Bahia_Banderas",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "BB",
        "countryName": "Barbados",
        "zoneName": "America/Barbados",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Belem",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "BZ",
        "countryName": "Belize",
        "zoneName": "America/Belize",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Blanc-Sablon",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Boa_Vista",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CO",
        "countryName": "Colombia",
        "zoneName": "America/Bogota",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Boise",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Cambridge_Bay",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Campo_Grande",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Cancun",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "VE",
        "countryName": "Venezuela",
        "zoneName": "America/Caracas",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "GF",
        "countryName": "French Guiana",
        "zoneName": "America/Cayenne",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "KY",
        "countryName": "Cayman Islands",
        "zoneName": "America/Cayman",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Chicago",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Chihuahua",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Ciudad_Juarez",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "CR",
        "countryName": "Costa Rica",
        "zoneName": "America/Costa_Rica",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Creston",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Cuiaba",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CW",
        "countryName": "Curacao",
        "zoneName": "America/Curacao",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "GL",
        "countryName": "Greenland",
        "zoneName": "America/Danmarkshavn",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Dawson",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Dawson_Creek",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Denver",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Detroit",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "DM",
        "countryName": "Dominica",
        "zoneName": "America/Dominica",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Edmonton",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Eirunepe",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "SV",
        "countryName": "El Salvador",
        "zoneName": "America/El_Salvador",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Fort_Nelson",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Fortaleza",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Glace_Bay",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Goose_Bay",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "TC",
        "countryName": "Turks and Caicos Islands",
        "zoneName": "America/Grand_Turk",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "GD",
        "countryName": "Grenada",
        "zoneName": "America/Grenada",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "GP",
        "countryName": "Guadeloupe",
        "zoneName": "America/Guadeloupe",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "GT",
        "countryName": "Guatemala",
        "zoneName": "America/Guatemala",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "EC",
        "countryName": "Ecuador",
        "zoneName": "America/Guayaquil",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "GY",
        "countryName": "Guyana",
        "zoneName": "America/Guyana",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Halifax",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CU",
        "countryName": "Cuba",
        "zoneName": "America/Havana",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Hermosillo",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Indianapolis",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Knox",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Marengo",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Petersburg",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Tell_City",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Vevay",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Vincennes",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Indiana/Winamac",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Inuvik",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Iqaluit",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "JM",
        "countryName": "Jamaica",
        "zoneName": "America/Jamaica",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Juneau",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Kentucky/Louisville",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Kentucky/Monticello",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "BQ",
        "countryName": "Bonaire, Saint Eustatius and Saba",
        "zoneName": "America/Kralendijk",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BO",
        "countryName": "Bolivia",
        "zoneName": "America/La_Paz",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "PE",
        "countryName": "Peru",
        "zoneName": "America/Lima",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Los_Angeles",
        "gmtOffset": -28800,
        "timestamp": 1735685278
      },
      {
        "countryCode": "SX",
        "countryName": "Sint Maarten",
        "zoneName": "America/Lower_Princes",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Maceio",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "NI",
        "countryName": "Nicaragua",
        "zoneName": "America/Managua",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Manaus",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MF",
        "countryName": "Saint Martin",
        "zoneName": "America/Marigot",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MQ",
        "countryName": "Martinique",
        "zoneName": "America/Martinique",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Matamoros",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Mazatlan",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Menominee",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Merida",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Metlakatla",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Mexico_City",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "PM",
        "countryName": "Saint Pierre and Miquelon",
        "zoneName": "America/Miquelon",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Moncton",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Monterrey",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "UY",
        "countryName": "Uruguay",
        "zoneName": "America/Montevideo",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "MS",
        "countryName": "Montserrat",
        "zoneName": "America/Montserrat",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BS",
        "countryName": "Bahamas",
        "zoneName": "America/Nassau",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/New_York",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Nome",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Noronha",
        "gmtOffset": -7200,
        "timestamp": 1735706878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/North_Dakota/Beulah",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/North_Dakota/Center",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/North_Dakota/New_Salem",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "GL",
        "countryName": "Greenland",
        "zoneName": "America/Nuuk",
        "gmtOffset": -7200,
        "timestamp": 1735706878
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Ojinaga",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "PA",
        "countryName": "Panama",
        "zoneName": "America/Panama",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "SR",
        "countryName": "Suriname",
        "zoneName": "America/Paramaribo",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Phoenix",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "HT",
        "countryName": "Haiti",
        "zoneName": "America/Port-au-Prince",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "TT",
        "countryName": "Trinidad and Tobago",
        "zoneName": "America/Port_of_Spain",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Porto_Velho",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "PR",
        "countryName": "Puerto Rico",
        "zoneName": "America/Puerto_Rico",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CL",
        "countryName": "Chile",
        "zoneName": "America/Punta_Arenas",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Rankin_Inlet",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Recife",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Regina",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Resolute",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Rio_Branco",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Santarem",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "CL",
        "countryName": "Chile",
        "zoneName": "America/Santiago",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "DO",
        "countryName": "Dominican Republic",
        "zoneName": "America/Santo_Domingo",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "BR",
        "countryName": "Brazil",
        "zoneName": "America/Sao_Paulo",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "GL",
        "countryName": "Greenland",
        "zoneName": "America/Scoresbysund",
        "gmtOffset": -7200,
        "timestamp": 1735706878
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Sitka",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "BL",
        "countryName": "Saint Barthelemy",
        "zoneName": "America/St_Barthelemy",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/St_Johns",
        "gmtOffset": -12600,
        "timestamp": 1735701478
      },
      {
        "countryCode": "KN",
        "countryName": "Saint Kitts and Nevis",
        "zoneName": "America/St_Kitts",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "LC",
        "countryName": "Saint Lucia",
        "zoneName": "America/St_Lucia",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "VI",
        "countryName": "U.S. Virgin Islands",
        "zoneName": "America/St_Thomas",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "VC",
        "countryName": "Saint Vincent and the Grenadines",
        "zoneName": "America/St_Vincent",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Swift_Current",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "HN",
        "countryName": "Honduras",
        "zoneName": "America/Tegucigalpa",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "GL",
        "countryName": "Greenland",
        "zoneName": "America/Thule",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "MX",
        "countryName": "Mexico",
        "zoneName": "America/Tijuana",
        "gmtOffset": -28800,
        "timestamp": 1735685278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Toronto",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "VG",
        "countryName": "British Virgin Islands",
        "zoneName": "America/Tortola",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Vancouver",
        "gmtOffset": -28800,
        "timestamp": 1735685278
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Whitehorse",
        "gmtOffset": -25200,
        "timestamp": 1735688878
      },
      {
        "countryCode": "CA",
        "countryName": "Canada",
        "zoneName": "America/Winnipeg",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "America/Yakutat",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Casey",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Davis",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/DumontDUrville",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Antarctica/Macquarie",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Mawson",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/McMurdo",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Palmer",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Rothera",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Syowa",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Troll",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "AQ",
        "countryName": "Antarctica",
        "zoneName": "Antarctica/Vostok",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "SJ",
        "countryName": "Svalbard and Jan Mayen",
        "zoneName": "Arctic/Longyearbyen",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "YE",
        "countryName": "Yemen",
        "zoneName": "Asia/Aden",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Almaty",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "JO",
        "countryName": "Jordan",
        "zoneName": "Asia/Amman",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Anadyr",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Aqtau",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Aqtobe",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "TM",
        "countryName": "Turkmenistan",
        "zoneName": "Asia/Ashgabat",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Atyrau",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "IQ",
        "countryName": "Iraq",
        "zoneName": "Asia/Baghdad",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "BH",
        "countryName": "Bahrain",
        "zoneName": "Asia/Bahrain",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "AZ",
        "countryName": "Azerbaijan",
        "zoneName": "Asia/Baku",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "TH",
        "countryName": "Thailand",
        "zoneName": "Asia/Bangkok",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Barnaul",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "LB",
        "countryName": "Lebanon",
        "zoneName": "Asia/Beirut",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "KG",
        "countryName": "Kyrgyzstan",
        "zoneName": "Asia/Bishkek",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "BN",
        "countryName": "Brunei",
        "zoneName": "Asia/Brunei",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Chita",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "LK",
        "countryName": "Sri Lanka",
        "zoneName": "Asia/Colombo",
        "gmtOffset": 19800,
        "timestamp": 1735733878
      },
      {
        "countryCode": "SY",
        "countryName": "Syria",
        "zoneName": "Asia/Damascus",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "BD",
        "countryName": "Bangladesh",
        "zoneName": "Asia/Dhaka",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "TL",
        "countryName": "Timor Leste",
        "zoneName": "Asia/Dili",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "AE",
        "countryName": "United Arab Emirates",
        "zoneName": "Asia/Dubai",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "TJ",
        "countryName": "Tajikistan",
        "zoneName": "Asia/Dushanbe",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "CY",
        "countryName": "Cyprus",
        "zoneName": "Asia/Famagusta",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "PS",
        "countryName": "Palestinian Territory",
        "zoneName": "Asia/Gaza",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "PS",
        "countryName": "Palestinian Territory",
        "zoneName": "Asia/Hebron",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "VN",
        "countryName": "Vietnam",
        "zoneName": "Asia/Ho_Chi_Minh",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "HK",
        "countryName": "Hong Kong",
        "zoneName": "Asia/Hong_Kong",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "MN",
        "countryName": "Mongolia",
        "zoneName": "Asia/Hovd",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Irkutsk",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "ID",
        "countryName": "Indonesia",
        "zoneName": "Asia/Jakarta",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "ID",
        "countryName": "Indonesia",
        "zoneName": "Asia/Jayapura",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "IL",
        "countryName": "Israel",
        "zoneName": "Asia/Jerusalem",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "AF",
        "countryName": "Afghanistan",
        "zoneName": "Asia/Kabul",
        "gmtOffset": 16200,
        "timestamp": 1735730278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Kamchatka",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "PK",
        "countryName": "Pakistan",
        "zoneName": "Asia/Karachi",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "NP",
        "countryName": "Nepal",
        "zoneName": "Asia/Kathmandu",
        "gmtOffset": 20700,
        "timestamp": 1735734778
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Khandyga",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "IN",
        "countryName": "India",
        "zoneName": "Asia/Kolkata",
        "gmtOffset": 19800,
        "timestamp": 1735733878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Krasnoyarsk",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "MY",
        "countryName": "Malaysia",
        "zoneName": "Asia/Kuala_Lumpur",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "MY",
        "countryName": "Malaysia",
        "zoneName": "Asia/Kuching",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "KW",
        "countryName": "Kuwait",
        "zoneName": "Asia/Kuwait",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "MO",
        "countryName": "Macao",
        "zoneName": "Asia/Macau",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Magadan",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "ID",
        "countryName": "Indonesia",
        "zoneName": "Asia/Makassar",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "PH",
        "countryName": "Philippines",
        "zoneName": "Asia/Manila",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "OM",
        "countryName": "Oman",
        "zoneName": "Asia/Muscat",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "CY",
        "countryName": "Cyprus",
        "zoneName": "Asia/Nicosia",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Novokuznetsk",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Novosibirsk",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Omsk",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Oral",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "KH",
        "countryName": "Cambodia",
        "zoneName": "Asia/Phnom_Penh",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "ID",
        "countryName": "Indonesia",
        "zoneName": "Asia/Pontianak",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "KP",
        "countryName": "North Korea",
        "zoneName": "Asia/Pyongyang",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "QA",
        "countryName": "Qatar",
        "zoneName": "Asia/Qatar",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Qostanay",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "KZ",
        "countryName": "Kazakhstan",
        "zoneName": "Asia/Qyzylorda",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "SA",
        "countryName": "Saudi Arabia",
        "zoneName": "Asia/Riyadh",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Sakhalin",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "UZ",
        "countryName": "Uzbekistan",
        "zoneName": "Asia/Samarkand",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "KR",
        "countryName": "South Korea",
        "zoneName": "Asia/Seoul",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "CN",
        "countryName": "China",
        "zoneName": "Asia/Shanghai",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "SG",
        "countryName": "Singapore",
        "zoneName": "Asia/Singapore",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Srednekolymsk",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "TW",
        "countryName": "Taiwan",
        "zoneName": "Asia/Taipei",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "UZ",
        "countryName": "Uzbekistan",
        "zoneName": "Asia/Tashkent",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "GE",
        "countryName": "Georgia",
        "zoneName": "Asia/Tbilisi",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "IR",
        "countryName": "Iran",
        "zoneName": "Asia/Tehran",
        "gmtOffset": 12600,
        "timestamp": 1735726678
      },
      {
        "countryCode": "BT",
        "countryName": "Bhutan",
        "zoneName": "Asia/Thimphu",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "JP",
        "countryName": "Japan",
        "zoneName": "Asia/Tokyo",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Tomsk",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "MN",
        "countryName": "Mongolia",
        "zoneName": "Asia/Ulaanbaatar",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "CN",
        "countryName": "China",
        "zoneName": "Asia/Urumqi",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Ust-Nera",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "LA",
        "countryName": "Laos",
        "zoneName": "Asia/Vientiane",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Vladivostok",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Yakutsk",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "MM",
        "countryName": "Myanmar",
        "zoneName": "Asia/Yangon",
        "gmtOffset": 23400,
        "timestamp": 1735737478
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Asia/Yekaterinburg",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "AM",
        "countryName": "Armenia",
        "zoneName": "Asia/Yerevan",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "PT",
        "countryName": "Portugal",
        "zoneName": "Atlantic/Azores",
        "gmtOffset": -3600,
        "timestamp": 1735710478
      },
      {
        "countryCode": "BM",
        "countryName": "Bermuda",
        "zoneName": "Atlantic/Bermuda",
        "gmtOffset": -14400,
        "timestamp": 1735699678
      },
      {
        "countryCode": "ES",
        "countryName": "Spain",
        "zoneName": "Atlantic/Canary",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "CV",
        "countryName": "Cabo Verde",
        "zoneName": "Atlantic/Cape_Verde",
        "gmtOffset": -3600,
        "timestamp": 1735710478
      },
      {
        "countryCode": "FO",
        "countryName": "Faroe Islands",
        "zoneName": "Atlantic/Faroe",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "PT",
        "countryName": "Portugal",
        "zoneName": "Atlantic/Madeira",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "IS",
        "countryName": "Iceland",
        "zoneName": "Atlantic/Reykjavik",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "GS",
        "countryName": "South Georgia and the South Sandwich Islands",
        "zoneName": "Atlantic/South_Georgia",
        "gmtOffset": -7200,
        "timestamp": 1735706878
      },
      {
        "countryCode": "SH",
        "countryName": "Saint Helena",
        "zoneName": "Atlantic/St_Helena",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "FK",
        "countryName": "Falkland Islands",
        "zoneName": "Atlantic/Stanley",
        "gmtOffset": -10800,
        "timestamp": 1735703278
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Adelaide",
        "gmtOffset": 37800,
        "timestamp": 1735751878
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Brisbane",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Broken_Hill",
        "gmtOffset": 37800,
        "timestamp": 1735751878
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Darwin",
        "gmtOffset": 34200,
        "timestamp": 1735748278
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Eucla",
        "gmtOffset": 31500,
        "timestamp": 1735745578
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Hobart",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Lindeman",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Lord_Howe",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Melbourne",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Perth",
        "gmtOffset": 28800,
        "timestamp": 1735742878
      },
      {
        "countryCode": "AU",
        "countryName": "Australia",
        "zoneName": "Australia/Sydney",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "NL",
        "countryName": "Netherlands",
        "zoneName": "Europe/Amsterdam",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "AD",
        "countryName": "Andorra",
        "zoneName": "Europe/Andorra",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Astrakhan",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "GR",
        "countryName": "Greece",
        "zoneName": "Europe/Athens",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "RS",
        "countryName": "Serbia",
        "zoneName": "Europe/Belgrade",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "DE",
        "countryName": "Germany",
        "zoneName": "Europe/Berlin",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "SK",
        "countryName": "Slovakia",
        "zoneName": "Europe/Bratislava",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "BE",
        "countryName": "Belgium",
        "zoneName": "Europe/Brussels",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RO",
        "countryName": "Romania",
        "zoneName": "Europe/Bucharest",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "HU",
        "countryName": "Hungary",
        "zoneName": "Europe/Budapest",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "DE",
        "countryName": "Germany",
        "zoneName": "Europe/Busingen",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MD",
        "countryName": "Moldova",
        "zoneName": "Europe/Chisinau",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "DK",
        "countryName": "Denmark",
        "zoneName": "Europe/Copenhagen",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "IE",
        "countryName": "Ireland",
        "zoneName": "Europe/Dublin",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "GI",
        "countryName": "Gibraltar",
        "zoneName": "Europe/Gibraltar",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "GG",
        "countryName": "Guernsey",
        "zoneName": "Europe/Guernsey",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "FI",
        "countryName": "Finland",
        "zoneName": "Europe/Helsinki",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "IM",
        "countryName": "Isle of Man",
        "zoneName": "Europe/Isle_of_Man",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "TR",
        "countryName": "Turkey",
        "zoneName": "Europe/Istanbul",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "JE",
        "countryName": "Jersey",
        "zoneName": "Europe/Jersey",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Kaliningrad",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Kirov",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "UA",
        "countryName": "Ukraine",
        "zoneName": "Europe/Kyiv",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "PT",
        "countryName": "Portugal",
        "zoneName": "Europe/Lisbon",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "SI",
        "countryName": "Slovenia",
        "zoneName": "Europe/Ljubljana",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "GB",
        "countryName": "United Kingdom",
        "zoneName": "Europe/London",
        "gmtOffset": 0,
        "timestamp": 1735714078
      },
      {
        "countryCode": "LU",
        "countryName": "Luxembourg",
        "zoneName": "Europe/Luxembourg",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "ES",
        "countryName": "Spain",
        "zoneName": "Europe/Madrid",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MT",
        "countryName": "Malta",
        "zoneName": "Europe/Malta",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "AX",
        "countryName": "Aland Islands",
        "zoneName": "Europe/Mariehamn",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "BY",
        "countryName": "Belarus",
        "zoneName": "Europe/Minsk",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "MC",
        "countryName": "Monaco",
        "zoneName": "Europe/Monaco",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Moscow",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "NO",
        "countryName": "Norway",
        "zoneName": "Europe/Oslo",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "FR",
        "countryName": "France",
        "zoneName": "Europe/Paris",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "ME",
        "countryName": "Montenegro",
        "zoneName": "Europe/Podgorica",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "CZ",
        "countryName": "Czechia",
        "zoneName": "Europe/Prague",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "LV",
        "countryName": "Latvia",
        "zoneName": "Europe/Riga",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "IT",
        "countryName": "Italy",
        "zoneName": "Europe/Rome",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Samara",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "SM",
        "countryName": "San Marino",
        "zoneName": "Europe/San_Marino",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "BA",
        "countryName": "Bosnia and Herzegovina",
        "zoneName": "Europe/Sarajevo",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Saratov",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "UA",
        "countryName": "Ukraine",
        "zoneName": "Europe/Simferopol",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "MK",
        "countryName": "North Macedonia",
        "zoneName": "Europe/Skopje",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "BG",
        "countryName": "Bulgaria",
        "zoneName": "Europe/Sofia",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "SE",
        "countryName": "Sweden",
        "zoneName": "Europe/Stockholm",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "EE",
        "countryName": "Estonia",
        "zoneName": "Europe/Tallinn",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "AL",
        "countryName": "Albania",
        "zoneName": "Europe/Tirane",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Ulyanovsk",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "LI",
        "countryName": "Liechtenstein",
        "zoneName": "Europe/Vaduz",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "VA",
        "countryName": "Vatican",
        "zoneName": "Europe/Vatican",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "AT",
        "countryName": "Austria",
        "zoneName": "Europe/Vienna",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "LT",
        "countryName": "Lithuania",
        "zoneName": "Europe/Vilnius",
        "gmtOffset": 7200,
        "timestamp": 1735721278
      },
      {
        "countryCode": "RU",
        "countryName": "Russia",
        "zoneName": "Europe/Volgograd",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "PL",
        "countryName": "Poland",
        "zoneName": "Europe/Warsaw",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "HR",
        "countryName": "Croatia",
        "zoneName": "Europe/Zagreb",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "CH",
        "countryName": "Switzerland",
        "zoneName": "Europe/Zurich",
        "gmtOffset": 3600,
        "timestamp": 1735717678
      },
      {
        "countryCode": "MG",
        "countryName": "Madagascar",
        "zoneName": "Indian/Antananarivo",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "IO",
        "countryName": "British Indian Ocean Territory",
        "zoneName": "Indian/Chagos",
        "gmtOffset": 21600,
        "timestamp": 1735735678
      },
      {
        "countryCode": "CX",
        "countryName": "Christmas Island",
        "zoneName": "Indian/Christmas",
        "gmtOffset": 25200,
        "timestamp": 1735739278
      },
      {
        "countryCode": "CC",
        "countryName": "Cocos Islands",
        "zoneName": "Indian/Cocos",
        "gmtOffset": 23400,
        "timestamp": 1735737478
      },
      {
        "countryCode": "KM",
        "countryName": "Comoros",
        "zoneName": "Indian/Comoro",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "TF",
        "countryName": "French Southern Territories",
        "zoneName": "Indian/Kerguelen",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "SC",
        "countryName": "Seychelles",
        "zoneName": "Indian/Mahe",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "MV",
        "countryName": "Maldives",
        "zoneName": "Indian/Maldives",
        "gmtOffset": 18000,
        "timestamp": 1735732078
      },
      {
        "countryCode": "MU",
        "countryName": "Mauritius",
        "zoneName": "Indian/Mauritius",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "YT",
        "countryName": "Mayotte",
        "zoneName": "Indian/Mayotte",
        "gmtOffset": 10800,
        "timestamp": 1735724878
      },
      {
        "countryCode": "RE",
        "countryName": "Reunion",
        "zoneName": "Indian/Reunion",
        "gmtOffset": 14400,
        "timestamp": 1735728478
      },
      {
        "countryCode": "WS",
        "countryName": "Samoa",
        "zoneName": "Pacific/Apia",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "NZ",
        "countryName": "New Zealand",
        "zoneName": "Pacific/Auckland",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "PG",
        "countryName": "Papua New Guinea",
        "zoneName": "Pacific/Bougainville",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "NZ",
        "countryName": "New Zealand",
        "zoneName": "Pacific/Chatham",
        "gmtOffset": 49500,
        "timestamp": 1735763578
      },
      {
        "countryCode": "FM",
        "countryName": "Micronesia",
        "zoneName": "Pacific/Chuuk",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "CL",
        "countryName": "Chile",
        "zoneName": "Pacific/Easter",
        "gmtOffset": -18000,
        "timestamp": 1735696078
      },
      {
        "countryCode": "VU",
        "countryName": "Vanuatu",
        "zoneName": "Pacific/Efate",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "TK",
        "countryName": "Tokelau",
        "zoneName": "Pacific/Fakaofo",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "FJ",
        "countryName": "Fiji",
        "zoneName": "Pacific/Fiji",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "TV",
        "countryName": "Tuvalu",
        "zoneName": "Pacific/Funafuti",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "EC",
        "countryName": "Ecuador",
        "zoneName": "Pacific/Galapagos",
        "gmtOffset": -21600,
        "timestamp": 1735692478
      },
      {
        "countryCode": "PF",
        "countryName": "French Polynesia",
        "zoneName": "Pacific/Gambier",
        "gmtOffset": -32400,
        "timestamp": 1735681678
      },
      {
        "countryCode": "SB",
        "countryName": "Solomon Islands",
        "zoneName": "Pacific/Guadalcanal",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "GU",
        "countryName": "Guam",
        "zoneName": "Pacific/Guam",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "US",
        "countryName": "United States",
        "zoneName": "Pacific/Honolulu",
        "gmtOffset": -36000,
        "timestamp": 1735678078
      },
      {
        "countryCode": "KI",
        "countryName": "Kiribati",
        "zoneName": "Pacific/Kanton",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "KI",
        "countryName": "Kiribati",
        "zoneName": "Pacific/Kiritimati",
        "gmtOffset": 50400,
        "timestamp": 1735764478
      },
      {
        "countryCode": "FM",
        "countryName": "Micronesia",
        "zoneName": "Pacific/Kosrae",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "MH",
        "countryName": "Marshall Islands",
        "zoneName": "Pacific/Kwajalein",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "MH",
        "countryName": "Marshall Islands",
        "zoneName": "Pacific/Majuro",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "PF",
        "countryName": "French Polynesia",
        "zoneName": "Pacific/Marquesas",
        "gmtOffset": -34200,
        "timestamp": 1735679878
      },
      {
        "countryCode": "UM",
        "countryName": "United States Minor Outlying Islands",
        "zoneName": "Pacific/Midway",
        "gmtOffset": -39600,
        "timestamp": 1735674478
      },
      {
        "countryCode": "NR",
        "countryName": "Nauru",
        "zoneName": "Pacific/Nauru",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "NU",
        "countryName": "Niue",
        "zoneName": "Pacific/Niue",
        "gmtOffset": -39600,
        "timestamp": 1735674478
      },
      {
        "countryCode": "NF",
        "countryName": "Norfolk Island",
        "zoneName": "Pacific/Norfolk",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "NC",
        "countryName": "New Caledonia",
        "zoneName": "Pacific/Noumea",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "AS",
        "countryName": "American Samoa",
        "zoneName": "Pacific/Pago_Pago",
        "gmtOffset": -39600,
        "timestamp": 1735674478
      },
      {
        "countryCode": "PW",
        "countryName": "Palau",
        "zoneName": "Pacific/Palau",
        "gmtOffset": 32400,
        "timestamp": 1735746478
      },
      {
        "countryCode": "PN",
        "countryName": "Pitcairn",
        "zoneName": "Pacific/Pitcairn",
        "gmtOffset": -28800,
        "timestamp": 1735685278
      },
      {
        "countryCode": "FM",
        "countryName": "Micronesia",
        "zoneName": "Pacific/Pohnpei",
        "gmtOffset": 39600,
        "timestamp": 1735753678
      },
      {
        "countryCode": "PG",
        "countryName": "Papua New Guinea",
        "zoneName": "Pacific/Port_Moresby",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "CK",
        "countryName": "Cook Islands",
        "zoneName": "Pacific/Rarotonga",
        "gmtOffset": -36000,
        "timestamp": 1735678078
      },
      {
        "countryCode": "MP",
        "countryName": "Northern Mariana Islands",
        "zoneName": "Pacific/Saipan",
        "gmtOffset": 36000,
        "timestamp": 1735750078
      },
      {
        "countryCode": "PF",
        "countryName": "French Polynesia",
        "zoneName": "Pacific/Tahiti",
        "gmtOffset": -36000,
        "timestamp": 1735678078
      },
      {
        "countryCode": "KI",
        "countryName": "Kiribati",
        "zoneName": "Pacific/Tarawa",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "TO",
        "countryName": "Tonga",
        "zoneName": "Pacific/Tongatapu",
        "gmtOffset": 46800,
        "timestamp": 1735760878
      },
      {
        "countryCode": "UM",
        "countryName": "United States Minor Outlying Islands",
        "zoneName": "Pacific/Wake",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      },
      {
        "countryCode": "WF",
        "countryName": "Wallis and Futuna",
        "zoneName": "Pacific/Wallis",
        "gmtOffset": 43200,
        "timestamp": 1735757278
      }
    ]
  }
```




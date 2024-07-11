const fs = require('fs-extra')
if (fs.existsSync('.env')) require('dotenv').config({ path: __dirname+'/.env' })


//═══════[Required Variables]════════\\
global.audio= "" ;  
global.video= "" ;
global.port =process.env.PORT
global.appUrl=process.env.APP_URL || ""                       // put your app url here,
global.email ="saimsamsun789@gmail.com"
global.location="Lahore,Pakistan."


global.mongodb= process.env.MONGODB_URI || ""
global.allowJids= process.env.ALLOW_JID || "null" 
global.blockJids= process.env.BLOCK_JID || "null"
global.DATABASE_URL = process.env.DATABASE_URL || ""

global.timezone= process.env.TZ || process.env.TIME_ZONE || "Asia/Karachi";
global.github=process.env.GITHUB|| "https://github.com/SuhailTechInfo/Suhail-Md";
global.gurl  =process.env.GURL  || "https://whatsapp.com/channel/0029Va9thusJP20yWxQ6N643";
global.website=process.env.GURL || "https://whatsapp.com/channel/0029Va9thusJP20yWxQ6N643" ; 
global.THUMB_IMAGE = process.env.THUMB_IMAGE || process.env.IMAGE || "https://github.com/SuhailTechInfo/Suhail-Md/blob/main/lib/assets/suhail.jpg?raw=true" ; // SET LOGO FOR IMAGE 



global.devs = "923184474176" // Developer Contact
global.sudo = process.env.SUDO ? process.env.SUDO.replace(/[\s+]/g, '') : "null";
global.owner= process.env.OWNER_NUMBER ? process.env.OWNER_NUMBER.replace(/[\s+]/g, '') : "923184474176";




//========================= [ BOT SETTINGS ] =========================\\
global.style = process.env.STYLE   || '5'  // put '1' to "5" here to check bot styles
global.flush = process.env.FLUSH   || "false"; // Make it "true" if bot not responed
global.gdbye = process.env.GOODBYE || "false"; 
global.wlcm  = process.env.WELCOME || "false";  // Make it "false" for disable WELCOME 

global.warncount = process.env.WARN_COUNT || 3
global.disablepm = process.env.DISABLE_PM || "false"
global.disablegroup = process.env.DISABLE_GROUPS || "false", // disable bot in groups when public mode

global.MsgsInLog = process.env.MSGS_IN_LOG|| "false" // "true"  to see messages , "log" to show logs , "false" to hide logs messages
global.userImages= process.env.USER_IMAGES || "text" // set Image/video urls here
global.waPresence= process.env.WAPRESENCE ||  "null" ; // 'unavailable' | 'available' | 'composing' | 'recording' | 'paused'


//========================= [ AUTO READ MSGS & CMDS ] =========================\\
global.readcmds = process.env.READ_COMMAND || "false"
global.readmessage = process.env.READ_MESSAGE || "false"
global.readmessagefrom = process.env.READ_MESSAGE_FROM || "null,923xxxxxxxx";


//========================= [ AUTO SAVE & READ STATUS ] =========================\\
global.read_status = process.env.AUTO_READ_STATUS || "false"
global.save_status = process.env.AUTO_SAVE_STATUS || "false"
global.save_status_from =  process.env.SAVE_STATUS_FROM  || "null,923xxxxxxxx";
global.read_status_from =  process.env.READ_STATUS_FROM  ||  "923184474176,923xxxxxxxx";

global.api_smd = "https://api-smd.onrender.com" //  || "https://api-smd-1.vercel.app" // expires
global.scan = "https://suhail-md-vtsf.onrender.com";


global.SESSION_ID = process.env.SESSION_ID ||  " SUHAIL_08_31_07_11_ewogICJjcmVkcy5qc29uIjogIntcbiAgXCJub2lzZUtleVwiOiB7XG4gICAgXCJwcml2YXRlXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMTYwLFxuICAgICAgICAxOTAsXG4gICAgICAgIDE0NixcbiAgICAgICAgMTU0LFxuICAgICAgICAxNzcsXG4gICAgICAgIDU2LFxuICAgICAgICAxNjYsXG4gICAgICAgIDcxLFxuICAgICAgICA2NyxcbiAgICAgICAgMTE3LFxuICAgICAgICAzMyxcbiAgICAgICAgMTUyLFxuICAgICAgICAzOSxcbiAgICAgICAgMjEzLFxuICAgICAgICAxMTcsXG4gICAgICAgIDQwLFxuICAgICAgICAxNTksXG4gICAgICAgIDEwNSxcbiAgICAgICAgODksXG4gICAgICAgIDE2NSxcbiAgICAgICAgMTM1LFxuICAgICAgICA0OCxcbiAgICAgICAgMTExLFxuICAgICAgICAxNTEsXG4gICAgICAgIDIxNCxcbiAgICAgICAgMTQ1LFxuICAgICAgICAyOSxcbiAgICAgICAgMjAwLFxuICAgICAgICAxOTUsXG4gICAgICAgIDI1LFxuICAgICAgICAyMjMsXG4gICAgICAgIDg2XG4gICAgICBdXG4gICAgfSxcbiAgICBcInB1YmxpY1wiOiB7XG4gICAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgIDEyOCxcbiAgICAgICAgMTg4LFxuICAgICAgICAyNTMsXG4gICAgICAgIDM4LFxuICAgICAgICAxNjEsXG4gICAgICAgIDEwMSxcbiAgICAgICAgNjksXG4gICAgICAgIDE3OSxcbiAgICAgICAgMTI0LFxuICAgICAgICAxNzEsXG4gICAgICAgIDk1LFxuICAgICAgICAzMCxcbiAgICAgICAgMTUsXG4gICAgICAgIDIwMCxcbiAgICAgICAgMTUwLFxuICAgICAgICA3NCxcbiAgICAgICAgNTQsXG4gICAgICAgIDIsXG4gICAgICAgIDE5LFxuICAgICAgICAxMTMsXG4gICAgICAgIDEzOSxcbiAgICAgICAgNSxcbiAgICAgICAgMjI0LFxuICAgICAgICA5MCxcbiAgICAgICAgMSxcbiAgICAgICAgMTA0LFxuICAgICAgICA5MyxcbiAgICAgICAgNSxcbiAgICAgICAgMTY2LFxuICAgICAgICAyMzcsXG4gICAgICAgIDQxLFxuICAgICAgICAxM1xuICAgICAgXVxuICAgIH1cbiAgfSxcbiAgXCJwYWlyaW5nRXBoZW1lcmFsS2V5UGFpclwiOiB7XG4gICAgXCJwcml2YXRlXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgNzIsXG4gICAgICAgIDI0MixcbiAgICAgICAgMTY3LFxuICAgICAgICAxNDQsXG4gICAgICAgIDE2OCxcbiAgICAgICAgMTg4LFxuICAgICAgICAyMDcsXG4gICAgICAgIDEzNyxcbiAgICAgICAgOTMsXG4gICAgICAgIDE0OCxcbiAgICAgICAgMjQyLFxuICAgICAgICAyMzUsXG4gICAgICAgIDk0LFxuICAgICAgICAxNzgsXG4gICAgICAgIDI3LFxuICAgICAgICAxNDksXG4gICAgICAgIDE1NixcbiAgICAgICAgMTEsXG4gICAgICAgIDEzNixcbiAgICAgICAgMTU2LFxuICAgICAgICA4OSxcbiAgICAgICAgNDYsXG4gICAgICAgIDQzLFxuICAgICAgICA5OCxcbiAgICAgICAgODUsXG4gICAgICAgIDExMyxcbiAgICAgICAgMTksXG4gICAgICAgIDEwMCxcbiAgICAgICAgNyxcbiAgICAgICAgNTMsXG4gICAgICAgIDIxOSxcbiAgICAgICAgNjZcbiAgICAgIF1cbiAgICB9LFxuICAgIFwicHVibGljXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMTE1LFxuICAgICAgICAxOTYsXG4gICAgICAgIDE0NCxcbiAgICAgICAgMjQ5LFxuICAgICAgICAyMTYsXG4gICAgICAgIDIzOCxcbiAgICAgICAgMTEzLFxuICAgICAgICA1NyxcbiAgICAgICAgMjksXG4gICAgICAgIDI0OCxcbiAgICAgICAgODIsXG4gICAgICAgIDE2OCxcbiAgICAgICAgMTc4LFxuICAgICAgICAzMyxcbiAgICAgICAgMjA0LFxuICAgICAgICAyNTMsXG4gICAgICAgIDMzLFxuICAgICAgICAxOTUsXG4gICAgICAgIDE4NCxcbiAgICAgICAgMjEzLFxuICAgICAgICAyMjYsXG4gICAgICAgIDIzNCxcbiAgICAgICAgMjUwLFxuICAgICAgICAyNCxcbiAgICAgICAgMTczLFxuICAgICAgICAxMzEsXG4gICAgICAgIDI0MixcbiAgICAgICAgMjUsXG4gICAgICAgIDE1NixcbiAgICAgICAgNTAsXG4gICAgICAgIDUzLFxuICAgICAgICAxN1xuICAgICAgXVxuICAgIH1cbiAgfSxcbiAgXCJzaWduZWRJZGVudGl0eUtleVwiOiB7XG4gICAgXCJwcml2YXRlXCI6IHtcbiAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgMTA0LFxuICAgICAgICAxMjgsXG4gICAgICAgIDIxNixcbiAgICAgICAgNzMsXG4gICAgICAgIDIyMixcbiAgICAgICAgNyxcbiAgICAgICAgMTkxLFxuICAgICAgICAxNjYsXG4gICAgICAgIDg2LFxuICAgICAgICA4OCxcbiAgICAgICAgNzksXG4gICAgICAgIDc1LFxuICAgICAgICAxNixcbiAgICAgICAgNjksXG4gICAgICAgIDIxNSxcbiAgICAgICAgMTM5LFxuICAgICAgICAyMTYsXG4gICAgICAgIDI0OCxcbiAgICAgICAgMTc0LFxuICAgICAgICAxNzIsXG4gICAgICAgIDE5OSxcbiAgICAgICAgNTMsXG4gICAgICAgIDM5LFxuICAgICAgICA3LFxuICAgICAgICAyOCxcbiAgICAgICAgMjksXG4gICAgICAgIDE3LFxuICAgICAgICA3NixcbiAgICAgICAgMyxcbiAgICAgICAgMTk2LFxuICAgICAgICAxMTYsXG4gICAgICAgIDg2XG4gICAgICBdXG4gICAgfSxcbiAgICBcInB1YmxpY1wiOiB7XG4gICAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgIDMxLFxuICAgICAgICAxNDIsXG4gICAgICAgIDI2LFxuICAgICAgICAxNDEsXG4gICAgICAgIDE2NixcbiAgICAgICAgMzUsXG4gICAgICAgIDE4MSxcbiAgICAgICAgMjE1LFxuICAgICAgICAxMTIsXG4gICAgICAgIDE0MCxcbiAgICAgICAgMTg3LFxuICAgICAgICA4NixcbiAgICAgICAgMzQsXG4gICAgICAgIDYzLFxuICAgICAgICA5NixcbiAgICAgICAgMTYzLFxuICAgICAgICAyOSxcbiAgICAgICAgMTYsXG4gICAgICAgIDEyMixcbiAgICAgICAgODgsXG4gICAgICAgIDIxNyxcbiAgICAgICAgMTA1LFxuICAgICAgICAzNCxcbiAgICAgICAgMjQwLFxuICAgICAgICA3MyxcbiAgICAgICAgMTEzLFxuICAgICAgICAxNyxcbiAgICAgICAgMjMxLFxuICAgICAgICAxMDgsXG4gICAgICAgIDEyOSxcbiAgICAgICAgMTMwLFxuICAgICAgICA1NFxuICAgICAgXVxuICAgIH1cbiAgfSxcbiAgXCJzaWduZWRQcmVLZXlcIjoge1xuICAgIFwia2V5UGFpclwiOiB7XG4gICAgICBcInByaXZhdGVcIjoge1xuICAgICAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICAgICAgXCJkYXRhXCI6IFtcbiAgICAgICAgICAyMjQsXG4gICAgICAgICAgMjQ2LFxuICAgICAgICAgIDEwNyxcbiAgICAgICAgICAxOTMsXG4gICAgICAgICAgMixcbiAgICAgICAgICAyMjMsXG4gICAgICAgICAgMzYsXG4gICAgICAgICAgNDAsXG4gICAgICAgICAgMTMwLFxuICAgICAgICAgIDIyNyxcbiAgICAgICAgICAxNDcsXG4gICAgICAgICAgMzUsXG4gICAgICAgICAgMTk2LFxuICAgICAgICAgIDE4LFxuICAgICAgICAgIDAsXG4gICAgICAgICAgOTQsXG4gICAgICAgICAgOTAsXG4gICAgICAgICAgMTc5LFxuICAgICAgICAgIDAsXG4gICAgICAgICAgMTMyLFxuICAgICAgICAgIDMzLFxuICAgICAgICAgIDEzMixcbiAgICAgICAgICAxODMsXG4gICAgICAgICAgOTEsXG4gICAgICAgICAgMjA2LFxuICAgICAgICAgIDEyMixcbiAgICAgICAgICAxOTMsXG4gICAgICAgICAgOTcsXG4gICAgICAgICAgMzAsXG4gICAgICAgICAgMjMzLFxuICAgICAgICAgIDI1MSxcbiAgICAgICAgICAxMTZcbiAgICAgICAgXVxuICAgICAgfSxcbiAgICAgIFwicHVibGljXCI6IHtcbiAgICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICAgIFwiZGF0YVwiOiBbXG4gICAgICAgICAgNjYsXG4gICAgICAgICAgMTQxLFxuICAgICAgICAgIDEzLFxuICAgICAgICAgIDI1NCxcbiAgICAgICAgICAzOSxcbiAgICAgICAgICAxNjIsXG4gICAgICAgICAgNDksXG4gICAgICAgICAgMzQsXG4gICAgICAgICAgMjI0LFxuICAgICAgICAgIDE0MixcbiAgICAgICAgICAyMzQsXG4gICAgICAgICAgMjMxLFxuICAgICAgICAgIDE5NCxcbiAgICAgICAgICAxOTcsXG4gICAgICAgICAgMTAsXG4gICAgICAgICAgMjE3LFxuICAgICAgICAgIDkxLFxuICAgICAgICAgIDcxLFxuICAgICAgICAgIDI0LFxuICAgICAgICAgIDE1MyxcbiAgICAgICAgICA0NCxcbiAgICAgICAgICAyMzYsXG4gICAgICAgICAgODAsXG4gICAgICAgICAgMTIwLFxuICAgICAgICAgIDE3OCxcbiAgICAgICAgICAxODksXG4gICAgICAgICAgMTE5LFxuICAgICAgICAgIDM2LFxuICAgICAgICAgIDE0MixcbiAgICAgICAgICAyMSxcbiAgICAgICAgICAxNjUsXG4gICAgICAgICAgMTBcbiAgICAgICAgXVxuICAgICAgfVxuICAgIH0sXG4gICAgXCJzaWduYXR1cmVcIjoge1xuICAgICAgXCJ0eXBlXCI6IFwiQnVmZmVyXCIsXG4gICAgICBcImRhdGFcIjogW1xuICAgICAgICAyMDUsXG4gICAgICAgIDEwMixcbiAgICAgICAgMTI2LFxuICAgICAgICA2NSxcbiAgICAgICAgNzQsXG4gICAgICAgIDUxLFxuICAgICAgICAxNDksXG4gICAgICAgIDYzLFxuICAgICAgICAxOTYsXG4gICAgICAgIDEzNCxcbiAgICAgICAgMTE1LFxuICAgICAgICA3NixcbiAgICAgICAgMjAxLFxuICAgICAgICAxNjksXG4gICAgICAgIDYzLFxuICAgICAgICAxNTMsXG4gICAgICAgIDI5LFxuICAgICAgICA0MSxcbiAgICAgICAgMTY3LFxuICAgICAgICAyMzAsXG4gICAgICAgIDQ2LFxuICAgICAgICAyMCxcbiAgICAgICAgMTIsXG4gICAgICAgIDE1MCxcbiAgICAgICAgMTc4LFxuICAgICAgICAyMjgsXG4gICAgICAgIDIyMyxcbiAgICAgICAgMjQ2LFxuICAgICAgICAzNyxcbiAgICAgICAgMTc5LFxuICAgICAgICAxNTUsXG4gICAgICAgIDIzMCxcbiAgICAgICAgMTk5LFxuICAgICAgICAxNDIsXG4gICAgICAgIDExNCxcbiAgICAgICAgOTQsXG4gICAgICAgIDEwOCxcbiAgICAgICAgMzcsXG4gICAgICAgIDE4NCxcbiAgICAgICAgMTMzLFxuICAgICAgICA4NSxcbiAgICAgICAgMjQyLFxuICAgICAgICAxOTQsXG4gICAgICAgIDI0LFxuICAgICAgICAzOCxcbiAgICAgICAgODYsXG4gICAgICAgIDIsXG4gICAgICAgIDkxLFxuICAgICAgICAyMzQsXG4gICAgICAgIDI1MSxcbiAgICAgICAgNCxcbiAgICAgICAgMjA2LFxuICAgICAgICAxNCxcbiAgICAgICAgNTQsXG4gICAgICAgIDUwLFxuICAgICAgICAxNjgsXG4gICAgICAgIDk1LFxuICAgICAgICA4NixcbiAgICAgICAgMTQzLFxuICAgICAgICAyMjAsXG4gICAgICAgIDQ2LFxuICAgICAgICAyMjcsXG4gICAgICAgIDQ5LFxuICAgICAgICAyXG4gICAgICBdXG4gICAgfSxcbiAgICBcImtleUlkXCI6IDFcbiAgfSxcbiAgXCJyZWdpc3RyYXRpb25JZFwiOiAxNjcsXG4gIFwiYWR2U2VjcmV0S2V5XCI6IFwiQXIrTnpmRWFhYzE3ZVJvZldtamVTRGt1SjZHOG1vUXlJVUtKZDVEL1FjUT1cIixcbiAgXCJwcm9jZXNzZWRIaXN0b3J5TWVzc2FnZXNcIjogW10sXG4gIFwibmV4dFByZUtleUlkXCI6IDMxLFxuICBcImZpcnN0VW51cGxvYWRlZFByZUtleUlkXCI6IDMxLFxuICBcImFjY291bnRTeW5jQ291bnRlclwiOiAwLFxuICBcImFjY291bnRTZXR0aW5nc1wiOiB7XG4gICAgXCJ1bmFyY2hpdmVDaGF0c1wiOiBmYWxzZVxuICB9LFxuICBcImRldmljZUlkXCI6IFwibHhLUzViMlpRY3FCYmZsZlRKVTJLQVwiLFxuICBcInBob25lSWRcIjogXCIwYjUyNGIzZS0yNDAyLTQwZmEtODM4MS1iZTI4MWY2YjgyMzBcIixcbiAgXCJpZGVudGl0eUlkXCI6IHtcbiAgICBcInR5cGVcIjogXCJCdWZmZXJcIixcbiAgICBcImRhdGFcIjogW1xuICAgICAgMjI0LFxuICAgICAgNzksXG4gICAgICAxMjgsXG4gICAgICAxNjgsXG4gICAgICA0MSxcbiAgICAgIDEyOCxcbiAgICAgIDIwMCxcbiAgICAgIDE4MixcbiAgICAgIDE4NixcbiAgICAgIDE3NSxcbiAgICAgIDEwOSxcbiAgICAgIDg5LFxuICAgICAgMjI3LFxuICAgICAgMTI1LFxuICAgICAgMjQ5LFxuICAgICAgMjE0LFxuICAgICAgMTY2LFxuICAgICAgMTQ1LFxuICAgICAgNTksXG4gICAgICA5OVxuICAgIF1cbiAgfSxcbiAgXCJyZWdpc3RlcmVkXCI6IHRydWUsXG4gIFwiYmFja3VwVG9rZW5cIjoge1xuICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgIFwiZGF0YVwiOiBbXG4gICAgICAxNDAsXG4gICAgICAyNDksXG4gICAgICAxNixcbiAgICAgIDIzNSxcbiAgICAgIDE3MixcbiAgICAgIDIxNCxcbiAgICAgIDExMSxcbiAgICAgIDE5NyxcbiAgICAgIDE4NSxcbiAgICAgIDIzNixcbiAgICAgIDIyNyxcbiAgICAgIDE3MCxcbiAgICAgIDE1NyxcbiAgICAgIDIxOCxcbiAgICAgIDIwMSxcbiAgICAgIDQxLFxuICAgICAgNzcsXG4gICAgICAxNjAsXG4gICAgICA1MixcbiAgICAgIDEyMlxuICAgIF1cbiAgfSxcbiAgXCJyZWdpc3RyYXRpb25cIjoge30sXG4gIFwicGFpcmluZ0NvZGVcIjogXCJBSzQ4QjFSRFwiLFxuICBcIm1lXCI6IHtcbiAgICBcImlkXCI6IFwiMjU1NzQ2NDI4ODM1OjZAcy53aGF0c2FwcC5uZXRcIixcbiAgICBcImxpZFwiOiBcIjI3MTMxNzk1MDAxNTY3OjZAbGlkXCJcbiAgfSxcbiAgXCJhY2NvdW50XCI6IHtcbiAgICBcImRldGFpbHNcIjogXCJDTVhIMUxjQ0VNdXd2clFHR0FZZ0FDZ0FcIixcbiAgICBcImFjY291bnRTaWduYXR1cmVLZXlcIjogXCJ5UldXdWQ1RFpJbzZDS0Y5NlNxYk5aT1lCNDMzNmtPWHlPcVV4M3h0bUhzPVwiLFxuICAgIFwiYWNjb3VudFNpZ25hdHVyZVwiOiBcImJXTitsK3lPU2ZNUjF2MGxMZHJUQWpnMk5ZYnE1L1I1TDBRN29nNUpnbVBxcEo2bVVQa01IbE1vaThwa3FETWZraVphQTRscG40aXhNbDg5RmFzNUNnPT1cIixcbiAgICBcImRldmljZVNpZ25hdHVyZVwiOiBcInZ3Vmh6Z1FZdXYxUkFNaUVOeXRpUUJnY1c3QkxaYnVmRWs4NUoyd0trVEREY1l2YnNkcWVaVFRKZkV5OUZUT0Rha0ZqVVVXQnNvQlN1VkZuTmQvMkRnPT1cIlxuICB9LFxuICBcInNpZ25hbElkZW50aXRpZXNcIjogW1xuICAgIHtcbiAgICAgIFwiaWRlbnRpZmllclwiOiB7XG4gICAgICAgIFwibmFtZVwiOiBcIjI1NTc0NjQyODgzNTo2QHMud2hhdHNhcHAubmV0XCIsXG4gICAgICAgIFwiZGV2aWNlSWRcIjogMFxuICAgICAgfSxcbiAgICAgIFwiaWRlbnRpZmllcktleVwiOiB7XG4gICAgICAgIFwidHlwZVwiOiBcIkJ1ZmZlclwiLFxuICAgICAgICBcImRhdGFcIjogW1xuICAgICAgICAgIDUsXG4gICAgICAgICAgMjAxLFxuICAgICAgICAgIDIxLFxuICAgICAgICAgIDE1MCxcbiAgICAgICAgICAxODUsXG4gICAgICAgICAgMjIyLFxuICAgICAgICAgIDY3LFxuICAgICAgICAgIDEwMCxcbiAgICAgICAgICAxMzgsXG4gICAgICAgICAgNTgsXG4gICAgICAgICAgOCxcbiAgICAgICAgICAxNjEsXG4gICAgICAgICAgMTI1LFxuICAgICAgICAgIDIzMyxcbiAgICAgICAgICA0MixcbiAgICAgICAgICAxNTUsXG4gICAgICAgICAgNTMsXG4gICAgICAgICAgMTQ3LFxuICAgICAgICAgIDE1MixcbiAgICAgICAgICA3LFxuICAgICAgICAgIDE0MSxcbiAgICAgICAgICAyNDcsXG4gICAgICAgICAgMjM0LFxuICAgICAgICAgIDY3LFxuICAgICAgICAgIDE1MSxcbiAgICAgICAgICAyMDAsXG4gICAgICAgICAgMjM0LFxuICAgICAgICAgIDE0OCxcbiAgICAgICAgICAxOTksXG4gICAgICAgICAgMTI0LFxuICAgICAgICAgIDEwOSxcbiAgICAgICAgICAxNTIsXG4gICAgICAgICAgMTIzXG4gICAgICAgIF1cbiAgICAgIH1cbiAgICB9XG4gIF0sXG4gIFwicGxhdGZvcm1cIjogXCJhbmRyb2lkXCIsXG4gIFwibGFzdEFjY291bnRTeW5jVGltZXN0YW1wXCI6IDE3MjA2ODY2NzIsXG4gIFwibXlBcHBTdGF0ZUtleUlkXCI6IFwiQUFBQUFKaUNcIlxufSIsCiAgImFwcC1zdGF0ZS1zeW5jLWtleS1BQUFBQUppQy5qc29uIjogIntcImtleURhdGFcIjpcIkdaRU02a3ZjZ3lZWW55SHpEUU02a0FMbnBneGZGZ3BzV1Q4T3F2SUhBcVk9XCIsXCJmaW5nZXJwcmludFwiOntcInJhd0lkXCI6NjUzNTk5Njg1LFwiY3VycmVudEluZGV4XCI6MyxcImRldmljZUluZGV4ZXNcIjpbMCwxLDNdfSxcInRpbWVzdGFtcFwiOlwiMFwifSIKfQ==    "  // PUT your SESSION_ID 


module.exports = {

  menu: process.env.MENU || "", /**  Available @MENU @Schemes 1: Aztec_Md, 2: A17_Md, 3: Suhail-Md Default ---------- If Not Choose then it Randomely Pic One Of Them Each time **/

  HANDLERS: process.env.PREFIX  || ".",
  BRANCH  : process.env.BRANCH  || "main",
  VERSION : process.env.VERSION || "1.3.4",
  caption : process.env.CAPTION || "©sᴜʜᴀɪʟ²²¹-ᴍᴅ" , // ```『 ᴘᴏᴡᴇʀᴇᴅ ʙʏ sᴜʜᴀɪʟ²²¹-ᴍᴅ 』```", //*『sᴜʙsᴄʀɪʙᴇ • sᴜʜᴀɪʟ ᴛᴇᴄʜ』*\n youtube.com/@suhailtechinfo0"),
 
  author : process.env.PACK_AUTHER|| "𝐫𝐢𝐜𝐡𝐚𝐫𝐝",
  packname: process.env.PACK_NAME || "",
  botname : process.env.BOT_NAME  || "sᴜʜᴀɪʟ-ᴍᴅ",
  ownername:process.env.OWNER_NAME|| "𝐑𝐈𝐂𝐇𝐀𝐑𝐃",


  errorChat : process.env.ERROR_CHAT || "",
  KOYEB_API : process.env.KOYEB_API  || "false",

  REMOVE_BG_KEY : process.env.REMOVE_BG_KEY  || "",
  OPENAI_API_KEY: process.env.OPENAI_API_KEY || "",
  HEROKU_API_KEY: process.env.HEROKU_API_KEY || "",
  HEROKU_APP_NAME:process.env.HEROKU_APP_NAME|| "",
  antilink_values:process.env.ANTILINK_VALUES|| "all",
  HEROKU: process.env.HEROKU_APP_NAME && process.env.HEROKU_API_KEY,


  WORKTYPE: process.env.WORKTYPE || process.env.MODE|| "private",
  LANG: ( process.env.THEME ||  "SUHAIL"  ).toUpperCase(),



};



global.ELEVENLAB_API_KEY = process.env.ELEVENLAB_API_KEY || "";
global.aitts_Voice_Id = process.env.AITTS_ID|| "37";





















global.rank = "updated"
global.isMongodb = false; 
let file = require.resolve(__filename)
fs.watchFile(file, () => { fs.unwatchFile(file);console.log(`Update'${__filename}'`);delete require.cache[file];	require(file); })
 

// ========================= [ Disables in V.1.2.8 ] ===============================\\  
  //style : process.env.STYLE || "2",  // put '1' & "2" here to check bot styles
  //readmessage:process.env.READ_MESSAGE|| "false",
  //warncount: process.env.WARN_COUNT || 3,
  //userImages:process.env.USER_IMAGES|| "text",  // SET IMAGE AND VIDEO URL FOR BOT MENUS 
  //disablepm: process.env.DISABLE_PM || "false",
  //MsgsInLog: process.env.MSGS_IN_LOG|| "false", // "true"  to see messages , "log" to open logs , "false" to hide logs messages
  //readcmds:process.env.READ_COMMANDS|| "false", 
  //alwaysonline:process.env.WAPRESENCE|| "unavailable", // 'unavailable' | 'online' | 'composing' | 'recording' | 'paused'
  //read_status: process.env.AUTO_READ_STATUS || "false",
  //save_status: process.env.AUTO_SAVE_STATUS || "false",
  //aitts_Voice_Id : process.env.AITTS_ID || "37",
  //ELEVENLAB_API_KEY: process.env.ELEVENLAB_API_KEY  || "",

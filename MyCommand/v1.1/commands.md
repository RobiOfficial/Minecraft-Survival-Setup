'help':
  command: /help
  type: ICON_MENU
  text:
  - 'POSITION:ITEM_NAME:ITEMDATA:COMMAND/MESSAGE:TITLE:DESCRIPTION;MULTILINES'
  iconmenu_title: '&cHelp'
  iconmenu_size: 57
  iconmenu_commands:
  - '10:DIRT:10:/warp wild:&a&lWilderness:&eStart your adventure!'
  - '12:BOOK:12:/rules:&a&lRules:&eServer rules!'
  - '14:LOG:14:%openiconmenu%/jobs browse:&a&lJobs:&eList of jobs!'
  - '16:PAPER:16:%openiconmenu%/warps:&a&lWarps:&eList of warps!'
  - '28:BEDROCK:28:/spawn:&a&lSpawnpoint:&eTeleport back to spawn.'
  - '30:DIAMOND:30:%openiconmenu%/shop:&a&lShop:&eBuy or sell items.'
  - '32:CHEST:32:%openiconmenu%/ah:&a&lAcution:&eAccess to auction system!'
  - '34:BARRIER:34:/report:&a&lReport:&eCreate a report ticket if needed.'
  permission-required: false
  permission-node: mycommand.cmd.help
  permission-error: "&a$player! , &2You can't use this command!"
  
'warps':
  command: /warps
  type: ICON_MENU
  text:
  - 'POSITION:ITEM_NAME:ITEMDATA:COMMAND/MESSAGE:TITLE:DESCRIPTION;MULTILINES'
  iconmenu_title: 'Warps'
  iconmenu_size: 9
  iconmenu_commands:
  - '0:CHEST:0:/warp Crates:&3Crates'
  - '1:BOOK:1:/warp Enchantment:&3Enchantment'
  permission-required: false
  permission-node: mycommand.cmd.warps
  permission-error: "&a$player! , &2You can't use this command!"

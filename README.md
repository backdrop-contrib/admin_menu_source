# Admin Menu Source

Choose a custom source menu for the Admin Bar per role. Only roles with
*access administration bar* permission are eligible.

## Requirements:
- Menu module (core)
- Menu Tools module (for snapshots/restores)

## Installation:
1. Download/clone into modules/contrib, then enable Menu Tools and Admin Menu Source at Administration → Modules.
2. Open Configuration → Administration → Admin Bar → Source (admin/config/administration/admin-bar/source) and pick a source menu for each eligible role.
3. Save source; the Admin Bar cache clears automatically.

## Documentation:

1. Use an existing menu or create a new menu for a Role.
2. Go to the Admin bar → Source tab and select the menu per role.
3. Save source; caches are cleared automatically.

Note: When creating menus, the top-level menu item is ignored, this is due to
the Admin Bar in core being hard wired. See the admin page for this module
for examples.

Additional documentation is located in the Wiki: https://github.com/backdrop-contrib/admin_menu_source/wiki

## Issues:
Bugs and Feature requests should be reported in the Issue Queue: https://github.com/backdrop-contrib/admin_menu_source/issues

## Current Maintainer(s):
- [Steve Moorhouse (albanycomputers)](https://github.com/albanycomputers)
- [Alan Mels](https://github.com/alanmels)
- Additional maintainers welcome

## Credits:

### Original Authors 
[shadcn (shadcn)](https://www.drupal.org/u/shadcn)

## Sponsorship:
 - [Albany Computer Services](https://www.albany-computers.co.uk)

## License
This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

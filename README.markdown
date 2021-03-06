SpreadSheetTableView for CPTableView!
=====================================

What is SpreadSheetTableView ?
------------------------------
SpreadSheetTableView is a small library for Cappuccino to use a CPTableView as a SpreadSheet (Numbers or Excel style keyboard navigation).
The actual features allow you to move easily in a CPTableView cell by cell with the arrows/tab/shift+tab.

SpreadSheetTableView will call the same delegate's methods and dataSource's methods as a CPTableView.

Getting Started
---------------
To build it

    # jake debug ; jake release

Then include the SpreadSheetTableView framework in your Frameworks directory and include SpreadSheetTableView.j

    @import <SpreadSheetTableView/SpreadSheetTableView.j>

Now create a SpreadSheetTableView like you do for a CPTableView (it works with xCode also)

Demo application
----------------

https://github.com/coalkids/SpreadSheetTableView-Example

License
-------
This library is free software; you can redistribute it and/or modify it under
the terms of the GNU Lesser General Public License as published by the Free
Software Foundation; either version 2.1 of the License, or (at your option)
any later version.

This library is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more
details.

You should have received a copy of the GNU Lesser General Public License along
with this library; if not, write to the Free Software Foundation, Inc., 51
Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA
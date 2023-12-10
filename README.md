# NY-Sanitation-Project

This repository provides code for optimizing resource allocation in waste management using a prediction model. This code uses New York City sanitation data that includes average weather, population of a particular borough, community district, and business type to predict trash tonnage.

A Python 3.x environment needs to be installed in order to execute this code successfully.

Bug reports are welcome.

# Appendix

As a reference, the following is taken from the problem declaration:

You can find data from New York Sanitation at
https://data.cityofnewyork.us/City-Government/DSNY-Monthly-Tonnage-Data/ebb7-mvp5

Labels:

1. Amount of Tonnage (per type of trash)
2. RefuseTons
3. PaperTons
4. MGPTons
5. ResOrganicTons
6. SchoolOrganicTons
7. LeavesOrganicTons
8. XmasTreeTons

Features:

1. Business type
2. Community District
3. Weather (monthly basis)
 https://www.ncdc.noaa.gov/cdo-web/datasets  
4. Population
   by borough, but decennial only https://data.cityofnewyork.us/City-Government/New-York-City-Population-by-Borough-1950-2040/xywu-7bv9 
5. Month
6. Optional: Aggregate sanitation data to a borough level (See Rodent data)”

# License

There are no restrictions on the use of this program: it may be redistributed and/or modified under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY, without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.

TableWithTableFooter
====================

CodeIgniter Table helper library with Table Footer (tfoot) support

created to scratch my own itch, published to encourage others to do the same.

Answers: http://stackoverflow.com/questions/13916646/how-to-add-a-tfoot-row-to-table-generated-with-codeigniter-table-class

h2. To install:

# download MY_Table.php file
# copy My_Table.php to htdocs/application/libraries/MY_Table.php
# if necessary change the file name to your extended library prefix, google how to do that

h2. To use:

#  $this->load->library('table');
#  $this->table->set_footer('tfoot_cell1', 'tfoot_cell2');  // just like set_header

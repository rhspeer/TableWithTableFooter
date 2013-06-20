TableWithTableFooter
====================

CodeIgniter Table helper library with Table Footer (tfoot) support

created to scratch my own itch, published to encourage others to do the same.

Answers: http://stackoverflow.com/questions/13916646/how-to-add-a-tfoot-row-to-table-generated-with-codeigniter-table-class

## To install:

1. download MY_Table.php file
1. copy My_Table.php to htdocs/application/libraries/MY_Table.php
1. if necessary change the file name to your extended library prefix, google how to do that

## To use:

1. $this->load->library('table');
1. $this->table->set_footer('tfoot_cell1', 'tfoot_cell2');  // just like set_header


## Disclaimer: 

This works, but I don't even like CodeIgnigher so it proably looks like it. Do your own testing.  
I am using it production, and intend to make fixes as necessary.

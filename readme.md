


# lib_extra_actions_c8oforms

<div>Extra Convertigo actions for No Code Studio.</div>


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [forms_total_responses](#forms_total_responses)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_extra_actions_c8oforms=https://github.com/convertigo/c8oprj-lib-extra-actions-nocode.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_extra_actions_c8oforms=https://github.com/convertigo/c8oprj-lib-extra-actions-nocode/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_extra_actions_c8oforms__ project


## Sequences

### forms_total_responses

<div>Count form responses. The form has to integrate an invisible Input component named '<b>index</b>'. This must be the first form action. The index value will be updated in the form response when submitted and can be used for CSV export or in email action using the '<b>__c8o_index</b>' pattern</div>

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>doc</td><td><div>Form responses</div></td>
</tr>
<tr>
<td>originalDoc</td><td><div>Original form document</div></td>
</tr>
</table>




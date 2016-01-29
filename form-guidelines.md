# Form guidelines

These are guidelines around how to design form fields and ways we can make them more inclusive and accessible.

## The question protocol

[http://www.uxmatters.com/mt/archives/2010/06/the-question-protocol-how-to-make-sure-every-form-field-is-necessary.php](http://www.uxmatters.com/mt/archives/2010/06/the-question-protocol-how-to-make-sure-every-form-field-is-necessary.php)

Each question you ask a user has a cost. Users may not use the form if it is too long or asks irrelevant questions. The question protocol is a good pattern to follow to make sure every field is useful

* Who needs the information?
* How are they going to use it?
* Is it required?
* Could this block a user from continuing?
* If it is required, what happens if the answer is not true? 

##Help text

Put help text in a localisation file in the project. If there is not a file, create on in the config/locales folder called forms.yml. See the Rails docs for more info. [http://guides.rubyonrails.org/i18n.html#translations-for-active-record-models](http://guides.rubyonrails.org/i18n.html#translations-for-active-record-models)

## Forms of address

As not all cultures and languages fit the first name/full name pattern, it is better to ask a user for their full name. The full name field should not have character restriction.

Titles should be optional as they are not a legal requirement for a name and can exclude people of other cultures and people with non-binary genders. It should be a text box where possible, or offer a text box with an 'other' option. 

## Gender

Gender should never be required. Use a text box, or allow options for 'non-binary' and 'agender' as well as 'prefer not to say'. 



# Part III - Interaction Design Practice with Glom

## Example Evaluation

To get you started, the brief example below represents the type of analysis we are looking for. **Your own analysis should be much more in depth!**

The sample interface provides a _Date_ field, however from a user perspective it is unclear how to format the input. For example, we could enter many different variations:

- dd/mm/yyyy
- mm/dd/yyyy
- dd-mm-yyyy
- mm-dd-yyyy
- yyyy-m-d
- yyyy-mm-dd
- ...

In addition, the label of this field does not effectively communicate the intended purpose. Is the date supposed to represent the day the scene was shot? Or is the date supposed to represent the current date the entry was created?

An improvement could be to add a placeholder value so users are able to see the intended format, or even better add a date selector widget where users can easily choose the required date and not worry about the input representation.

**_You would continue this analysis by tying this particular control to specific UI communication principles._**

## Evaluate Glom's Communication with Users

1. Find examples within the user interface that detract from a clear and intuitive user experience.

> Formulate your discussion in terms of *controls *(words)*, *commands (verbs)* and *dialogue (labels/instructions/feedback)*.
> Provide specific examples from the interface (highlight screenshots if necessary) when applicable in your analysis (~2 paragraphs).

First, the biggest issue I found was what I believe to be a couple of progress command buttons in the options below. This makes the flow very unclear. What are the first and last ones? Can I click on them? Secondly, why do you need to list the first two steps separately? Are they special in any way? I think users will find the command of the button here very confusing. Their problems are: And the top two buttons are equally confusing. What happens when you click them? Why doesn't the interface change much between clicked and unclicked? 1. not intuitive 2. information overload, so that the user can not quickly choose 3. not intuitive enough. Generally, there will be only two buttons below, and four will make the user is not very familiar with the design. If the user selects the option according to intuition, they are likely to choose the last step and try to choose the next step. 4. there are actually a total of six buttons underneath, but there is no clear a hierarchy between them. Then the user will think that their logical relationship is juxtaposed. But apparently not. The hierarchy here is also not clear and straightforward enough.  and the affordance of the buttons is not obvious enough. If the default is next, he should encourage the user to click a button. But 4 identical buttons would make the user not know where to click the most. Don't make users think. If you want to highlight that the first and last steps are essential, it would be better to have some explanation or have a progress bar on top showing all the steps and where they are now (clearly marking the difference between the steps now). And which steps are completed and which are not. Having said that, it is necessary, the first and last step can be highlighted with a different color / or another sign.
Another issue is the hierarchy of the whole page. For example, whether there are many underlines in the window or dashed lines. Generally, underlining will be recognized as having an external link. Underlining is not used very often in design, even when emphasizing particular text. It is understandable that the original design may have wanted to use lines to distinguish different kinds of issues and spaces. But there are many flaws in such an approach. First of all, its essential elements, such as text and lines, are not aligned, and the spacing is not uniform. The structure seems confusing. The whole window does not have a systematic plan. This makes people feel less professional, and they can't find the focus and information they want to see. It is recommended to use Group boxes, as mentioned in the textbook.



2. Find 1-2 controls within the provided interface that violate the UI communication principles we have discussed.

> For each control, describe why the control as it is currently implemented does not effectively communicate with the end user (~1 paragraph).

The first problem is the two buttons at the top: list and details, and I don't know what the difference is between checking these two options. The information given here is very unclear. It is vaguely worded/misleadingly labeled. It is not straightforward enough. Secondly, the design of this button is not intuitive. Normally, buttons do not appear at the top of the design. We can say that this design is misleading because it shows the details being selected, but there is no obvious change. Secondly, the use of this control is also incorrect. If he wanted to switch pages, he could have done it in tab form. Or if this was an option, he could have used a radio button.
The second problem is the two options of the scenario. The biggest problem is that it is not straightforward enough. There could be a simpler way to select and present information. The label for this choice is also not clear. What exactly is the nature of this need for selection? He directly treats the choice as a label very inefficient. If improved, a direct Radio button would be a better choice. This would be much more straightforward and intutive.


## Glom Interface Redesign

### Sketches

Photograph your hand-drawn sketches and include them. Images must be visible in Markdown Preview for credit.
![avatar](/)


### Rationale

Provide a brief rationale about how your design addressed the communication issues you identified. This should probably be around 1-2 paragraphs.

Since hierarchy is a major issue. I reorganized the page with group boxes to make its structure clearer. I also changed the bottom list and details above to radio buttons to show relationships. And I think these two options are simple choices for the user. If they lead the user elsewhere, then the design needs to change. In addition, I changed the scene option to a radio button because it is more straightforward. With a 0/1 click, the user can make their choice. I also changed the buttons at the bottom. To differentiate them, I turned the add-delete text button into a smaller button with a straightforward logo. and placed them a bit above. I turned the four bottom right buttons into two and gave them different colors. If there is a real need to give the first and last page, then the designer needs to reconsider the change here.

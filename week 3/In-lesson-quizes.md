Quick Search and Basic Search

1. Assume that you enter the following into Jira's quick search. "item AND 1 NOT 2". Which one of the following statements is true?

        A. This is the same as entering "item 1 not 2".
        B. This is the same as entering "ITEM 1 not 2"
        C. This is the same as entering "item 1 NOT 2" .

        Ans: C
        Correct. "AND" keywords are assumed between search terms.

2. Which one of the following statements about basic search is true?

        A. You can use the "contains text" box to enter JQL.
        B. You can only select from one search criteria.
        C. You can use NOT in the "contains text" box to exclude text.

        Ans: C

JQL

3. Which one of these is NOT a part of a JQL query?

        A. Selecting a subset of issues.
        B. Ordering of results. 
        C. Updating the value of a field.

        Ans: C
        Correct. JQL is not used to update field values.

4. True/False. Clicking on a column header to change the sort order in basic search will change the underlying JQL.

        A. True
        B. False

        Ans: A

5. Which one of the following statements is true?

        A. If there are two fields in the ORDER BY clause, only the first field has any effect.
        B. You must include an ORDER BY clause to display search results.
        C. If your JQL query only has an ORDER BY clause, the results will contain all issues that you have permission to view.

        Ans: C
        Correct. By default a JQL query selects all issues.

6. Assume the following JQL query:
   created > startOfDay(-2d)
   Which one of the following statements is true?

        A. The "-2d" argument does not change the query results.
        B. This query only selects issues that were created in the past 48 hours.
        C. This query only selects issues that were created since the start of day two days ago.

        Ans: C

7. Which one of the following JQL queries will return only issues that are not currently assigned?

        A. assignee ~ empty
        B. assignee was empty
        C. assignee is empty

        Ans: C

8. True/False. These two queries are equivalent:
   (status = "Selected for Development" OR status = "To Do") AND summary ~ "item"
    status = "Selected for Development" OR status = "To Do" AND summary ~ "item"

        A. True, because this OR operator is evaluated first with or without the parentheses.
        B. True, because Boolean operators are always evaluated from left to right.
        C. False, because OR is evaluated first in the first query and AND is evaluated first in the second query.
        D. False, because AND is always evaluated before OR.

        Ans: C
        Correct. Everything else being equal, AND has precedence over OR.

Filters

9. Which one of the following statements is true?

        A. A filter is always private to the user who created it.
        B. Saving a search creates a filter.
        C. Filters can only be created in advanced search.

        Ans: B

10. Which one of the following statements is always true?

        A. A board's filter displays at least a single issue.
        B. A board's filter can display issues from multiple projects.
        C. A board's filter displays all issues of a single project.

        Ans: B

Issue Types

11. Which one of the following statements is true?

        A. An issue is a type of story.
        B. Issue type is represented as an issue's field.
        C. Custom issue types can not be created.

        Ans: B

12. When you create an issue, why is the "subtask" issue type not available?

        A. Because subtasks must have a parent issue.
        B. Because subtasks are not issues.
        C. Because "subtask" is not an issue type.

        Ans: A

13. Which one of the following statements is true?

        A. An issue type scheme only applies to one project.
        B. An issue type scheme may apply to more than one project.
        C. A change to an issue type scheme affects all projects in the Jira account.

        Ans: B

14. Which one of the following statements is true?

        A. To configure a swimlane based on issue type, navigate to the "Issues" tab for the project.
        B. Issue type can only be selected in advanced search.
        C. The "issuetype" field is used to identify an issue's type.

        Ans: C

Configuring Issues

15. True/False. Each issue must have at least one label. 

        A. True.
        B. False.

        Ans: B

15. Which of these statements is true?

        A. Project administrators and Jira administrators can configure screens for all project members.
        B. Any user can configure screens for all project members.
        C. Only Jira administrators can configure screens for all project members.

        Ans: A

15. Which one of the following statements about creating a custom field is true?

        A. You must select a custom field type.
        B. The custom field can not be displayed on Jira screens.
        C. The custom field will a required field.

        Ans: A





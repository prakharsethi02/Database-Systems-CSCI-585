<B>This assignment consists of five SQL Queries that are divided in two sets and their problem statements are given below</B>
<h2> Set 1: GoodReads database </h2>
<p>
GoodReads is a website that allows users to add books that they have read, review them and socialize with other people. They have hired you as their new database admin and provided you with access to their tables. They have some questions for you. Formulate queries for each of the questions.
<br>List of tables:
<br>Book: ISBN, Title, AuthorID, NumPages, AverageRating.
<br>Users: UID, Name, Age, Sex, Location, Birthday, ReadCount, CurrentlyReadingCount, ToReadCount Shelf: UID, ISBN, Rating, ShelfName, DateRead, DateAdded
<br>Friends: UID, FriendID
<br>Author: AuthorID, Name.
<br>Questions:
<br>1. User adds a new book to his shelf with a rating. Update the average rating of that book.
<br>2. Find the names of the common books that were read by any two users X and Y.
</p>
<br><h2> Set 2: GitHub Database </h2>
<br>Your start-up wants to make a Version Control System, and you are taking inspiration from GitHub to organize your work. You have identified some tables, and now you want to test your VCS by running a few queries.
<br>List of tables:
<br>Repository: RepoID, UserID, IssueCount, PullRequestCount, ProjectCount, Wiki (yes/no) Issues: IssueID, CreatorID, RaiseDate, ResolverID, ResolveDate.
<br>Code: RepoID, CommitCount, BranchCount, ReleaseCount, ContributorCount
<br>Commit: CommitID, BranchID, Timestamp, NumFiles, Additions, Deletions
<br>Branches: UserID, BranchID, RepoID
<br>User: UserID, NumRepos, Location, Email, Website, ContributionCount
<br>Questions:
<br>1. Find the users who made branches of either of repositories X or Y but not of a repository Z.
<br>2. Find the top commit with the highest lines of code reduced. (Hint: We need to find the maximized value of: number of deletions - number of additions in each commit).
<br>3. List the users who solved more issues than they raised. (i.e. number of issues in which they were the resolver is greater than the number of issues where they were the creator.)

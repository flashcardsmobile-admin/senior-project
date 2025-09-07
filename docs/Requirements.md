Requirements
=============

Requirement #1
--------------

**Description:** The product shall render the text of the Bible with chapter and verse numbers.

**Rationale:** This has been a standard feature of Bibles for centuries.

**Fit Criterion:** The verses should conform to the standard chapter/verse deliniations in the biblical text.

**Priority:** 1

Requirement #2
--------------

**Description:** The product shall allow the user to search for words within the biblical text.

**Rationale:** This feature is present in Logos/Concordance.

**Fit Criterion:** There shall be a search utility that peruses the text and returns the correct chapter/verse locations where the word appears in the text.

**Priority:** 1

Requirement #3
--------------

**Description:** The product shall allow the user to select a verse and see the parsing and lexical information in the original language.

**Rationale:** This feature is present in Logos/Concordance.

**Fit Criterion:** The feature shall present the words in the verse with lemmas, parsings, and lexicon entries when the verse is selected for more details.

**Priority:** 2

Requirement #4
--------------

**Description:** The product shall allow the user to select a verse and see where it is referenced in commentaries and the writings of the Church Fathers.

**Rationale:** This feature will make study more convenient.

**Fit Criterion:** The feature shall present the relevant references which can be opened in another in-application window.

**Priority:** 2

Requirement #5
--------------

**Description:** The product shall render its resources as a hypertext document using standard HTML features.

**Rationale:** This will allow the user to switch between resources trivially.

**Fit Criterion:** Extra interactions via JavaScript should be minimized.

**Priority:** 1

Requirement #6
--------------

**Description:** The product shall provide access to multiple public-domain English commentaries.

**Rationale:** This is helpful for study.

**Fit Criterion:** Multiple English commentaries should be available to the user.

**Priority:** 1

Requirement #7
--------------

**Description:** The product shall provide access to multiple public-domain English bibles.

**Rationale:** This is the whole reason for the product. With no bibles, we aren't a bible site.

**Fit Criterion:** The bibles should be of good quality and/or historical value and available to English-speaking users.

**Priority:** 1

Requirement #8
--------------

**Description:** The product shall provide access to English translations of the complete works of the Church Fathers.

**Rationale:** These are helpful for study in historical context.

**Fit Criterion:** The English translations of the works of the Church Fathers should be available to the user.

**Priority:** 1

Requirement #9
--------------

**Description:** The product shall hyperlink verse references in the commentaries and in the Church Fathers.

**Rationale:** This will allow for easy checking when reading the commentaries and Church Fathers directly.

**Fit Criterion:** The verse hyperlinks should open inside a Bible text in-app window.

**Priority:** 3

Requirement #10
--------------

**Description:** The product shall allow the user to see the Greek and Hebrew texts directly.

**Rationale:** This is helpful for study.

**Fit Criterion:** The product will switch the current content of the current biblical text window just like changing translations.

**Priority:** 1

Requirement #11
--------------

**Description:** The product shall allow the user to select the specific manuscript in Greek/Hebrew view.

**Rationale:** This will be helpful for study.

**Fit Criterion:** The manuscripts shown should be shown legibly.

**Priority:** 1

Requirement #12
--------------

**Description:** The product shall allow the user to compare different manuscripts.

**Rationale:** This is helpful for study.

**Fit Criterion:** The product will show a diff-like view to see the differences between the manuscripts.

**Priority:** 1

Requirement #13
--------------

**Description:** The product shall allow the user to create an account

**Rationale:** This is will enable note-taking.

**Fit Criterion:** The user shall be able to create an account and log in via an email/password.

**Priority:** 2

Requirement #14
--------------

**Description:** The product shall allow signed-in users to take notes.

**Rationale:** This is helpful for study.

**Fit Criterion:** The user's journal (stored via file, database, or similar) shall be only viewable by that user.

**Priority:** 2

Requirement #15
--------------

**Description:** The product shall allow the user to automatically create a vocab list from the Greek or Hebrew words found in a particular chapter/verse range.

**Rationale:** This is helpful for study in the original languages.

**Fit Criterion:** The product will export the vocab list in a printable format.

**Priority:** 3

Requirement #16
--------------

**Description:** The product shall allow the user to create and view flashcards automatically from the Greek or Hebrew words found in a particular chapter/verse range.

**Rationale:** This is helpful for study in the original languages.

**Fit Criterion:** The product will allow the flashcards to be perused in a similar way as FlashcardsMobile.

**Priority:** 3

Requirement #17
--------------

**Description:** The product shall allow the user to customize the font settings of the text for their user account.

**Rationale:** This is a convenience for the user.

**Fit Criterion:** The product will allow the font family and size to be selected from a list and saved to the user's account information.

**Priority:** 4

Requirement #18
--------------

**Description:** The product shall allow the user to modify text color and background color for their user account.

**Rationale:** This is a convenience for the user and gives them something to fiddle with to increase percieved investment in the platform.

**Fit Criterion:** The product will save the user's preference.

**Priority:** 2

Requirement #19
--------------

**Description:** The product shall allow the user to use a subset of org-style markup within notes.

**Rationale:** This is by far the superior form of markup. Other formats like Markdown cannot dream to have such power.

**Fit Criterion:** The product will allow the notes to use a subset of the Emacs org-mode markup language.

**Priority:** 4

Requirement #20
--------------

**Description:** The product shall allow logged-in users to select from a variety of public-domain English translations.

**Rationale:** This will allow the user to compare the opinions of a variety of translators instead of merely relying on one.

**Fit Criterion:** The product will save a variety of translations and allow them to be presented as hypertext.

**Priority:** 1

Requirement #21
--------------

**Description:** The product shall query CCEL for new information and pull it into the database during off-hours.

**Rationale:** This will allow for the system to automatically maintain itself.

**Fit Criterion:** The product system will pull in new ThML files and parse them in a manner where evaluation errors may be recovered from with a report of files requiring manual intervention.

**Priority:** 2

Requirement #22
--------------

**Description:** The product shall save snapshots of database state every day and before doing maintenance tasks.

**Rationale:** This will allow the system to be more tolerant of potential errors.

**Fit Criterion:** The product will save snapshots of database state in a manner that will allow for easy recovery.

**Priority:** 1

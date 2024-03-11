# Stella
Gallery for Stella, the AI-powered market research platform revealing the *constellations* in your data 

**Stella** provides researchers with a suite of tools to accelerate the workflows central to their work, including:

- Generative question-answering for **on-demand analysis** of primary sources
- **Structured notetaking** with data aggregation
- Development of **surveys, screeners, & discussion guides**, with portability to external formats

### Analysis on demand

In the **Analysis** module, users group primary sources from one or many projects for deeper interrogation.

For targetted question-answering, I designed an LLM network leveraging several specialized models to optimize intermediary tasks such information retrieval, filtering, and answer composition.

With this architecture, users can pose any question they wish to the chatbot, and for any valid questions (i.e. "What do (respondent type)s think of (topic)?"), so long as an eligible answer exists among the sources, the system locates the necessary information and constructs a report from the bottom-up.

##### Question dispatch
![Question dispatch](/gallery/QuestionDispatch.gif "Question dispatch")

Today, "hallucinations" are likely the main pitfall of AI solutions. To curb any doubt over the veracity of generated responses, the system produces citations pulled directly from the source.

For transcripts, cited sources come in the form of quotes cut from the original conversation, along with additional context inserted via square brackets. Alongside quotes, users may also review the surrounding context through selections included from the original transcript.

##### Answer expansion
![Respondent answer expansion](/gallery/RespondentAnswerExpansion.gif "Respondent answer expansion")

In-line tagging enables users to categorically annotate valuable selections. With embedded video, users may also play back the interview from the exact timestamp of the selection.  

##### Tagging and video playback
![Tagging and video playback](/gallery/TaggingAndVideoPlayback.gif "Tagging and video playback")

For deeper inspection, the transcript browser provides each transcript in its entirety, with complex boolean searching and tag filtering for immediate drill down.

##### Transcript browser
![Searching and tagging](/gallery/SearchingAndTagging.gif "Searching and tagging")

### Structured notetaking

For a more manual approach to synthesis, the **Notebook** module offers an editor to create a custom template with fields for questions types ranging from open-end, numeric, multi-select, and more!

Once a template is created, users can assign an interview session to it to complete the questionnaire.

##### Notetaking (single session)
![Notetaking](/gallery/Notetaking.gif "Notetaking")

For notetaking or review of multiple sessions, the **Notebook grid** provides a table to edit and read notes for all sessions in one pane.

##### Notebook grid (multiple sessions)
![Notebook grid](/gallery/NotebookGrid.gif "Notebook grid")

### Discussion guides

Document creation for assets such as **Discussion guides, Screeners, and Surveys** is also available, featuring a point-and-click interface providing the flexibility to create complex documents without sacrificing standardization.

![Discussion guide editor](/gallery/DiscussionGuideEditor.gif "Discussion guide editor")

# Teacher Service Architecture Documentation

The documentation here uses the [C4 model][c4model] by [Simon Brown][simonbrown].
We use the [FC4 toolset][fc4-toolset] to normalise the source of C4 diagrams authored with [Structurizr Express][se].

## Landscape diagram

The diagrams folder contains a a high-level map of the software systems. This diagram doesn't focus on any specific system and it shows the overall landscape of systems within the business. This is the highest possible “zoom level”.

 <img src="diagrams/teacher-services-landscape-diagram.png" width="780"/>

**n.b. The Teacher Services landscape diagram is still a first draft, and it is work in progress.**

## Structure

Teacher Services is divided into different service areas, with their respective locations in the repository.

| Service area | Location | Responsibility |
| ------------ | -------- | -------------- |
| Teacher trainee & provider data | [`diagrams/teacher-trainees-and-providers-data`](diagrams/teacher-trainees-and-providers-data)| Collates information from Initial Teacher Training (ITT) providers and makes it available to DfE to facilitate a range of business requirements |

## Conventions

### Colours

- Department for education software systems, people and elements use the ["Department for education" websafe colour][moj-websafe] (`#347ca9`).
- Software systems, people and elements outside the UK Government use `#28a197`.


[se]: https://structurizr.com/help/express
[c4model]: https://c4model.com/
[simonbrown]: http://simonbrown.je/
[fc4-toolset]: https://fundingcircle.github.io/fc4-framework/methodology/toolset.html
[moj-websafe]: https://github.com/alphagov/govuk_frontend_toolkit/blob/03204449dcbf28c2d48e7f6dd217f6abe9b3a518/stylesheets/colours/_organisation.scss#L17

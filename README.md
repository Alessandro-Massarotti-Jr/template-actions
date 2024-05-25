# template-actions

<p>
  <img src="https://img.shields.io/badge/made%20by-Alessandro%20Massarotti%20Jr-000000?style=flat-square">
</p>

Template actions for github projects, this repository has a feture to add actions files to some repositories when the workflows has any changes

## Sumary

- [template-actions](#template-actions)
  - [Sumary](#sumary)
  - [Actions](#actions)
    - [pull-request-openner](#pull-request-openner)
    - [release](#release)
    - [validations](#validations)

## Actions

This session is for talk about what each action on this repository do

### pull-request-openner

This action open a pull request to main branch when pull request to develop was closed.
See the file here: [pull-request-openner](./.github/actions/pull-request-openner.yaml)

### release
This action release a new version each time main branch has new pushs
update the main branch with changelog create version tag and update develop with new generated version
See the file here: [release](./.github/actions/release.yaml)


### validations
This action runs validotion checks on PR was openned to develop or main branches, the validation includes
- Unit tests
- Linter
- Build project check

See the file here: [validations](./.github/actions/validations.yaml)


<br>

---

Developed By [Alessandro Massarotti Jr](https://github.com/alessandro-massarotti-jr) 🤖
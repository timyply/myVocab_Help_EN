# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repo) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/timyply/myVocab_Help_EN/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/timyply/myVocab_Help_EN/DataSource/_data/supportdocs_datasource.json</a>

<details>
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/timyply/myVocab_Help_EN/DataSource/_data/supportdocs_datasource.json")!
    @State var supportDocsPresented = false
    
    var body: some View {
        Button("Present SupportDocs from SwiftUI!") { supportDocsPresented = true }
        .sheet(isPresented: $supportDocsPresented, content: {
            SupportDocsView(dataSource: dataSource, isPresented: $supportDocsPresented)
        })
    }
}
```

### UIKit
```swift
class UIKitExampleController_MinimalCode: UIViewController {
    /**
    Connect this inside the storyboard.
    
    This is just for demo purposes, so it's not connected yet.
    */
    @IBAction func presentButtonPressed(_ sender: Any) {
        let dataSource = URL(string: "https://raw.githubusercontent.com/timyply/myVocab_Help_EN/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://timyply.github.io/myVocab_Help_EN/404) (SupportDocs Integrated File) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/myVocab_Help_EN/404.md))
- [Ajout d'une langue](https://timyply.github.io/myVocab_Help_EN/Languages/Add) (languages) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/Languages/Add.md))
- [Fonctionnement](https://timyply.github.io/myVocab_Help_EN/Tests/HowWorks) (tests) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/Tests/HowWorks.md))
- [Premium version](https://timyply.github.io/myVocab_Help_EN/Purchases/VersionPremium) (purchases) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/Purchases/VersionPremium.md))
- [Suppression d'une langue](https://timyply.github.io/myVocab_Help_EN/Languages/Delete) (languages) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/Languages/Delete.md))
- [Suppression de cartes](https://timyply.github.io/myVocab_Help_EN/Cards/Delete) (cards) ([edit](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/Cards/Delete.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/timyply/myVocab_Help_EN/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/timyply/myVocab_Help_EN/edit/DataSource/_scripts/README.md). 
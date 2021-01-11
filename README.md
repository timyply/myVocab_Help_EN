# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repo) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/timyply/myVocab_Help_FR/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/timyply/myVocab_Help_FR/DataSource/_data/supportdocs_datasource.json</a>

<details>
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/timyply/myVocab_Help_FR/DataSource/_data/supportdocs_datasource.json")!
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
        let dataSource = URL(string: "https://raw.githubusercontent.com/timyply/myVocab_Help_FR/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://timyply.github.io/myVocab_Help_FR/404) (SupportDocs Integrated File) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/myVocab_Help_FR/404.md))
- [Ajout d'une langue](https://timyply.github.io/myVocab_Help_FR/Languages/Add) (languages) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Languages/Add.md))
- [Apple smoothie](https://timyply.github.io/myVocab_Help_FR/Sample-Smoothies/Apple) (smoothies) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Smoothies/Apple.md))
- [Blueberry smoothie](https://timyply.github.io/myVocab_Help_FR/Sample-Smoothies/Blueberry) (smoothies) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Smoothies/Blueberry.md))
- [Buy blue boba](https://timyply.github.io/myVocab_Help_FR/Sample-Boba/BuyBlueBoba) (boba) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Boba/BuyBlueBoba.md))
- [Buy cream boba](https://timyply.github.io/myVocab_Help_FR/Sample-Boba/BuyCreamBoba) (boba) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Boba/BuyCreamBoba.md))
- [Buy orange boba](https://timyply.github.io/myVocab_Help_FR/Sample-Boba/BuyOrangeBoba) (boba) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Boba/BuyOrangeBoba.md))
- [Fonctionnement](https://timyply.github.io/myVocab_Help_FR/Tests/HowWorks) (tests) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Tests/HowWorks.md))
- [How to cook pizza](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToCookPizza) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToCookPizza.md))
- [How to eat burritos](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToEatBurritos) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToEatBurritos.md))
- [How to eat grilled cheese](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToEatGrilledCheese) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToEatGrilledCheese.md))
- [How to eat nachos](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToEatNachos) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToEatNachos.md))
- [How to eat tacos](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToEatTacos) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToEatTacos.md))
- [How to make spaghetti](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToMakeSpaghetti) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToMakeSpaghetti.md))
- [How to prepare ramen](https://timyply.github.io/myVocab_Help_FR/Sample-FastFood/HowToPrepareRamen) (fastFood) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-FastFood/HowToPrepareRamen.md))
- [Peach smoothie](https://timyply.github.io/myVocab_Help_FR/Sample-Smoothies/Peach) (smoothies) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Smoothies/Peach.md))
- [Plum smoothie](https://timyply.github.io/myVocab_Help_FR/Sample-Smoothies/Plum) (smoothies) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Smoothies/Plum.md))
- [Red berry smoothie](https://timyply.github.io/myVocab_Help_FR/Sample-Smoothies/RedBerries) (smoothies) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Sample-Smoothies/RedBerries.md))
- [Suppression d'une langue](https://timyply.github.io/myVocab_Help_FR/Languages/Delete) (languages) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Languages/Delete.md))
- [Suppression de cartes](https://timyply.github.io/myVocab_Help_FR/Cards/Delete) (cards) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Cards/Delete.md))
- [Version Premium](https://timyply.github.io/myVocab_Help_FR/Purchases/VersionPremium) (purchases) ([edit](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/Purchases/VersionPremium.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/timyply/myVocab_Help_FR/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/timyply/myVocab_Help_FR/edit/DataSource/_scripts/README.md). 
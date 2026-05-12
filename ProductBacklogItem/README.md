
# Definition of terms

| PBL | Product Backlog | 
| --- | --- |
| PBI | Product Backlog Item |  
| SBL | Sprint Backlog | 

# Who can create a PBI?

## 1. Everyone can create a new item. But please follow the template.

Everyone can post a new item. Select an appropriate template and describe the details.

<aside>
💡 If you are not an engineer or an product manager, You should add a bug report item on the other form.

</aside>

## 2. The Product Manager will create a new item based on the roadmap or epic.

# PBI Types

Make sure to choose the template type when you create a new item. You can see the description of each type from here. [https://edwardearle.medium.com/the-6-backlog-item-types-bdd2e1ab450](https://edwardearle.medium.com/the-6-backlog-item-types-bdd2e1ab450)

PBIの種類は以下のように分類されます。該当するものを新規作成時にテンプレートから選択してください。

| Type | Description | Description | Sample |
| --- | --- | --- | --- |
| **Feature** (Same template) | What the user will be able to do that is new. In the user story, requirements/requests should be written briefly from the end user's perspective. If the content is larger, make it EPIC. | ユーザーが新しく出来るようになること。ユーザーストーリーでは、要件・リクエストをエンドユーザー目線で簡潔に書く。内容が大きくなる場合はEPICにする。 |  |
| Changes (Same template) | This is a change request for a function that has already been implemented. The functionality is not changed, but the method of implementation is changed. | 既に実装された機能に対する変更要求です。機能は変えず、実現方法を変更します。 | |
| **Business Requirements (Same template)** | This is a requirement that is not directly relevant to the user but necessary for the business. | ユーザーには直接関係ないが事業上必要な要件です。 |  |
| Defect | A modification to a Feature or Changes already provided to the user. Must be associated with one of the Features or Changes. | すでにユーザーに提供された Feature or Changesに対する修正。（いずれかのFeature or Changesと紐づける必要がある。） | |
| Debt | A bug with a low priority to fix that was compromised by changing the acceptance criteria for resolving the problem at release time. Or the development team had to take shortcuts that reduced the robustness of the product (perhaps code refactoring is effective or performance needs to be improved). Setup work that is not strictly functional for users at project or product launch (e.g., CI pipeline implementation, solution creation, etc.) can be counted as technical debt. | リリース時に問題の解決を受け入れ基準を変更して妥協した、修正の優先度が低いバグ。または、開発チームは、製品の堅牢性を低下させるような近道をしなければならなかった（おそらく、コードのリファクタリングが有効か、パフォーマンスを向上させる必要がある）。プロジェクトや製品の立ち上げ時に、ユーザーに対して厳密に機能を提供しないセットアップ作業（CIパイプラインの実装、ソリューションの作成など）を技術的負債としてカウントすることができる。 |  |
| Spike | This work investigates approaches to developing new features. | 新機能の開発アプローチを調査する作業です。 | |
| **Undone** | The PBI that can’t be accomplished in the previous sprint. |  |  |

## Status

| **New** | A product manager is preparing for evaluating return of an item. |
| --- | --- |
| Pending | This item is pending for some reasons |
| Planning / In Design | The product manager is planning or the designer is working on this item. |
| **Ready to implement** | The developers are ready to implement an item. |
| **In Progress** | The developers are implementing an item. |
|  |  |
| **Done/Staging** | The developers completed an implementation and it is staged. |
| Released | It has been released. |
| **Archived** | We found we don’t have to implement it because it is not appropriate. |

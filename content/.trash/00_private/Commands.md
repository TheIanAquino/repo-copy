`npx quartz --push --commit`: 
> Pushes and commits the changes from the vault.

`npx quartz sync`: 
> Updates the repository on GitHub.

`npx quartz build --serve`
> Previews the current look of the website on a local host (usually http://localhost:8080/)

---

`import { PageLayout, SharedLayout } from "./quartz/cfg"; import * as Component from "./quartz/components"; // Components shared across all pages export const sharedPageComponents: SharedLayout = { head: Component.Head(), header: [], // Removed the Discord and GitHub links from the footer footer: Component.Footer(), }; // Components for pages that display a single page (e.g. a single note) export const defaultContentPageLayout: PageLayout = { beforeBody: [ Component.Breadcrumbs(), Component.ArticleTitle(), Component.ContentMeta(), Component.TagList(), ], left: [ Component.PageTitle(), Component.MobileOnly(Component.Spacer()), Component.Search(), Component.Darkmode(), Component.DesktopOnly(Component.Explorer()), ], right: [ Component.Graph(), Component.DesktopOnly(Component.TableOfContents()), Component.Backlinks(), ], }; // Components for pages that display lists of pages (e.g. tags or folders) export const defaultListPageLayout: PageLayout = { beforeBody: [ Component.Breadcrumbs(), Component.ArticleTitle(), Component.ContentMeta(), ], left: [ Component.PageTitle(), Component.MobileOnly(Component.Spacer()), Component.Search(), Component.Darkmode(), Component.DesktopOnly(Component.Explorer()), ], right: [], };`

> Modified quartz.layout.ts

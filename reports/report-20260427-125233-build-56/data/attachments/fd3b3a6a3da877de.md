# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: account/change-account-owner-impersonation.spec.ts >> Account Owner Change - Impersonation and Ownership Transfer >> should change account owner via user impersonation and verify ownership transfer
- Location: tests/account/change-account-owner-impersonation.spec.ts:158:7

# Error details

```
Test timeout of 300000ms exceeded.
```

```
Error: page.screenshot: Target page, context or browser has been closed
```

# Page snapshot

```yaml
- generic [active]:
  - generic [ref=e2]:
    - generic [ref=e3]:
      - link "Skip to Navigation" [ref=e4] [cursor=pointer]:
        - /url: javascript:void(0);
      - link "Skip to Main Content" [ref=e5] [cursor=pointer]:
        - /url: javascript:void(0);
      - generic [ref=e8]:
        - img [ref=e12]
        - generic [ref=e15]: Logged in as Support Manager (support.manager@mailosaur.net)
        - link "Log out as Support Manager" [ref=e16] [cursor=pointer]:
          - /url: /secur/logout.jsp
      - generic [ref=e17]:
        - button "Search" [ref=e23]:
          - img [ref=e25]
          - text: Search...
        - navigation "Global Header" [ref=e28]:
          - list [ref=e30]:
            - listitem [ref=e31]:
              - group [ref=e32]:
                - button "Add favorite" [ref=e34] [cursor=pointer]:
                  - generic [ref=e35]:
                    - img [ref=e39]
                    - tooltip "Add favorite"
                - button "Favorites list" [ref=e43] [cursor=pointer]:
                  - generic [ref=e44]:
                    - img [ref=e48]
                    - tooltip "Favorites list"
            - listitem [ref=e51]:
              - button "Global Actions" [ref=e57] [cursor=pointer]:
                - generic [ref=e58]:
                  - img [ref=e62]
                  - tooltip "Global Actions"
            - listitem [ref=e65]:
              - button "Guidance Center" [ref=e67] [cursor=pointer]:
                - generic [ref=e68]:
                  - img [ref=e72]
                  - tooltip "Guidance Center"
            - listitem [ref=e75]:
              - button "Salesforce Help" [ref=e78] [cursor=pointer]:
                - generic [ref=e79]:
                  - img [ref=e83]
                  - tooltip "Salesforce Help"
            - listitem [ref=e86]:
              - button "Setup" [ref=e92] [cursor=pointer]:
                - generic [ref=e93]:
                  - img [ref=e97]
                  - tooltip "Setup"
            - listitem [ref=e100]:
              - button "Notifications" [ref=e103] [cursor=pointer]:
                - generic [ref=e104]:
                  - img [ref=e109]
                  - tooltip "Notifications"
            - listitem [ref=e113]:
              - button "View profile" [ref=e116] [cursor=pointer]:
                - generic [ref=e117]:
                  - tooltip "View profile"
    - generic [ref=e121]:
      - generic [ref=e124]:
        - generic [ref=e126]:
          - navigation "App" [ref=e127]:
            - button "App Launcher" [ref=e129] [cursor=pointer]:
              - generic [ref=e140]: App Launcher
          - heading "Sales" [level=1] [ref=e141]:
            - generic "Sales" [ref=e142]
        - navigation "Global" [ref=e145]:
          - list [ref=e146]:
            - listitem [ref=e147]:
              - link "Home" [ref=e148] [cursor=pointer]:
                - /url: /lightning/page/home
                - generic [ref=e149]: Home
            - listitem [ref=e150]:
              - link "Opportunities" [ref=e151] [cursor=pointer]:
                - /url: /lightning/o/Opportunity/home
                - generic [ref=e152]: Opportunities
              - button "Opportunities List" [ref=e156] [cursor=pointer]:
                - img [ref=e160]
                - generic [ref=e163]: Opportunities List
            - listitem [ref=e164]:
              - link "Leads" [ref=e165] [cursor=pointer]:
                - /url: /lightning/o/Lead/home
                - generic [ref=e166]: Leads
              - button "Leads List" [ref=e170] [cursor=pointer]:
                - img [ref=e174]
                - generic [ref=e177]: Leads List
            - listitem [ref=e178]:
              - link "Tasks" [ref=e179] [cursor=pointer]:
                - /url: /lightning/o/Task/home
                - generic [ref=e180]: Tasks
              - button "Tasks List" [ref=e184] [cursor=pointer]:
                - img [ref=e188]
                - generic [ref=e191]: Tasks List
            - listitem [ref=e192]:
              - link "Files" [ref=e193] [cursor=pointer]:
                - /url: /lightning/o/ContentDocument/home
                - generic [ref=e194]: Files
              - button "Files List" [ref=e198] [cursor=pointer]:
                - img [ref=e202]
                - generic [ref=e205]: Files List
            - listitem [ref=e206] [cursor=pointer]:
              - link "Accounts" [ref=e207]:
                - /url: /lightning/o/Account/home
                - generic [ref=e208]: Accounts
              - button "Accounts List" [ref=e212]:
                - img [ref=e216]
                - generic [ref=e219]: Accounts List
            - listitem [ref=e220]:
              - link "Contacts" [ref=e221] [cursor=pointer]:
                - /url: /lightning/o/Contact/home
                - generic [ref=e222]: Contacts
              - button "Contacts List" [ref=e226] [cursor=pointer]:
                - img [ref=e230]
                - generic [ref=e233]: Contacts List
            - listitem [ref=e234]:
              - link "Campaigns" [ref=e235] [cursor=pointer]:
                - /url: /lightning/o/Campaign/home
                - generic [ref=e236]: Campaigns
              - button "Campaigns List" [ref=e240] [cursor=pointer]:
                - img [ref=e244]
                - generic [ref=e247]: Campaigns List
            - listitem [ref=e248]:
              - link "Dashboards" [ref=e249] [cursor=pointer]:
                - /url: /lightning/o/Dashboard/home
                - generic [ref=e250]: Dashboards
              - button "Dashboards List" [ref=e254] [cursor=pointer]:
                - img [ref=e258]
                - generic [ref=e261]: Dashboards List
            - listitem [ref=e262]:
              - link "Reports" [ref=e263] [cursor=pointer]:
                - /url: /lightning/o/Report/home
                - generic [ref=e264]: Reports
              - button "Reports List" [ref=e268] [cursor=pointer]:
                - img [ref=e272]
                - generic [ref=e275]: Reports List
            - listitem [ref=e276]:
              - button "Show more navigation items" [ref=e278] [cursor=pointer]:
                - generic [ref=e279]: More
                - img [ref=e283]
                - generic [ref=e286]: Show more navigation items
            - listitem [ref=e287]:
              - button "Edit nav items" [ref=e289] [cursor=pointer]:
                - img [ref=e291]
                - generic [ref=e294]: Edit nav items
      - main [ref=e296]:
        - generic [ref=e306]:
          - generic [ref=e308]:
            - generic [ref=e309]:
              - generic [ref=e311]:
                - img [ref=e315]
                - generic [ref=e316]:
                  - heading "Accounts" [level=1] [ref=e320]
                  - generic [ref=e321]:
                    - generic [ref=e323] [cursor=pointer]:
                      - heading "Accounts Recently Viewed" [level=1] [ref=e324]:
                        - generic [ref=e325]: Accounts
                        - generic [ref=e326]: Recently Viewed
                      - 'button "Select a List View: Accounts" [ref=e329]':
                        - img [ref=e331]
                        - generic [ref=e334]: "Select a List View: Accounts"
                    - button "This list is pinned." [disabled] [ref=e338] [cursor=pointer]:
                      - img [ref=e340]
                      - generic [ref=e343]: This list is pinned.
              - list [ref=e346]:
                - listitem [ref=e347]:
                  - button "New" [ref=e348] [cursor=pointer]:
                    - generic "New" [ref=e349]
                - listitem [ref=e350]:
                  - button "Import" [ref=e351] [cursor=pointer]:
                    - generic "Import" [ref=e352]
                - listitem [ref=e353]:
                  - button "Assign Label" [ref=e354] [cursor=pointer]:
                    - generic "Assign Label" [ref=e355]
            - generic [ref=e356]:
              - paragraph [ref=e358]:
                - generic [ref=e360]:
                  - status "Recently Viewed" [ref=e361]: 4 items •
                  - text: Updated 4 minutes ago
              - generic [ref=e367]:
                - generic [ref=e368]: Search this list...
                - generic [ref=e369]:
                  - searchbox "Search this list..." [ref=e370]
                  - img [ref=e371]
              - generic [ref=e374]:
                - button "List View Controls" [ref=e378] [cursor=pointer]:
                  - img [ref=e380]
                  - img [ref=e384]
                  - generic [ref=e387]: List View Controls
                - button "Select list display" [ref=e390] [cursor=pointer]:
                  - img [ref=e392]
                  - img [ref=e396]
                  - generic [ref=e399]: Select list display
                - generic [ref=e401]:
                  - button "Refresh" [ref=e404] [cursor=pointer]:
                    - img [ref=e406]
                    - generic [ref=e409]: Refresh
                  - button "Column sort" [ref=e412] [cursor=pointer]:
                    - img [ref=e414]
                    - generic [ref=e417]: Column sort
                  - button "Edit List" [ref=e420] [cursor=pointer]:
                    - img [ref=e422]
                    - generic [ref=e425]: Edit List
                  - group [ref=e426]:
                    - generic [ref=e428]:
                      - generic:
                        - generic:
                          - button "Charts" [disabled]:
                            - generic:
                              - img
                            - generic: Charts
                      - generic:
                        - generic:
                          - button "Filters" [disabled]:
                            - generic:
                              - img
                            - generic: Filters
          - generic [ref=e435]:
            - generic [ref=e436]: Navigation Mode
            - grid [ref=e440]:
              - rowgroup:
                - row "Row Number Choose a Row Select 4 items Account Name Account Site Phone Account Owner Alias Action":
                  - columnheader "Row Number":
                    - generic [ref=e443]:
                      - generic "Row Number"
                  - gridcell "Choose a Row Select 4 items":
                    - generic [ref=e444]:
                      - generic [ref=e445]: Choose a Row
                      - generic [ref=e447]:
                        - checkbox "Select 4 items" [ref=e448]
                        - generic [ref=e451]: Select 4 items
                  - columnheader "Account Name":
                    - generic [ref=e453]:
                      - 'button "Sort by: Account Name" [ref=e454] [cursor=pointer]':
                        - generic [ref=e455]: "Sort by:"
                        - generic "Account Name" [ref=e456]
                      - generic [ref=e457]: "Sorted: None"
                      - button "Show Account Name column actions" [ref=e459] [cursor=pointer]:
                        - img [ref=e461]
                        - generic [ref=e464]: Show Account Name column actions
                      - slider "Account Name column width" [ref=e465]: "474"
                  - columnheader "Account Site":
                    - generic [ref=e469]:
                      - 'button "Sort by: Account Site" [ref=e470] [cursor=pointer]':
                        - generic [ref=e471]: "Sort by:"
                        - generic "Account Site" [ref=e472]
                      - generic [ref=e473]: "Sorted: None"
                      - button "Show Account Site column actions" [ref=e475] [cursor=pointer]:
                        - img [ref=e477]
                        - generic [ref=e480]: Show Account Site column actions
                      - slider "Account Site column width" [ref=e481]: "177"
                  - columnheader "Phone":
                    - generic [ref=e485]:
                      - 'button "Sort by: Phone" [ref=e486] [cursor=pointer]':
                        - generic [ref=e487]: "Sort by:"
                        - generic "Phone" [ref=e488]
                      - generic [ref=e489]: "Sorted: None"
                      - button "Show Phone column actions" [ref=e491] [cursor=pointer]:
                        - img [ref=e493]
                        - generic [ref=e496]: Show Phone column actions
                      - slider "Phone column width" [ref=e497]: "177"
                  - columnheader "Account Owner Alias":
                    - generic [ref=e501]:
                      - 'button "Sort by: Account Owner Alias" [ref=e502] [cursor=pointer]':
                        - generic [ref=e503]: "Sort by:"
                        - generic "Account Owner Alias" [ref=e504]
                      - generic [ref=e505]: "Sorted: None"
                      - button "Show Account Owner Alias column actions" [ref=e507] [cursor=pointer]:
                        - img [ref=e509]
                        - generic [ref=e512]: Show Account Owner Alias column actions
                      - slider "Account Owner Alias column width" [ref=e513]: "281"
                  - columnheader "Action":
                    - generic [ref=e518]:
                      - generic "Action"
              - rowgroup [ref=e519]:
                - row "Select Item 1 Choose a Row Test_Account Edit Account Name Edit Account Site Edit Phone suj Locked Account Owner Alias Show Actions" [ref=e520]:
                  - gridcell [ref=e521]
                  - gridcell "Select Item 1 Choose a Row" [ref=e525]:
                    - generic [ref=e526]:
                      - checkbox "Select Item 1 Choose a Row" [ref=e527]
                      - generic [ref=e530]: Select Item 1
                  - rowheader "Test_Account Edit Account Name" [ref=e531]:
                    - generic [ref=e532]:
                      - link "Test_Account" [ref=e538] [cursor=pointer]:
                        - /url: /lightning/r/001gL0000162zwHQAQ/view
                        - generic [ref=e539]: Test_Account
                      - button "Edit Account Name" [ref=e540] [cursor=pointer]:
                        - img [ref=e541]
                  - gridcell "Edit Account Site" [ref=e544]:
                    - button "Edit Account Site" [ref=e546] [cursor=pointer]:
                      - img [ref=e547]
                  - gridcell "Edit Phone" [ref=e550]:
                    - button "Edit Phone" [ref=e552] [cursor=pointer]:
                      - img [ref=e553]
                  - gridcell "suj Locked Account Owner Alias" [ref=e556]:
                    - generic [ref=e557]:
                      - link "suj" [ref=e562] [cursor=pointer]:
                        - /url: /lightning/r/005gL00000FABtiQAH/view
                        - generic [ref=e563]: suj
                      - img "Locked Account Owner Alias" [ref=e564]:
                        - img [ref=e565]
                  - gridcell "Show Actions" [ref=e568]:
                    - button "Show Actions" [ref=e574] [cursor=pointer]:
                      - img [ref=e576]
                      - generic [ref=e579]: Show Actions
                - row "Select Item 2 Choose a Row Test_Account Edit Account Name Edit Account Site Edit Phone smana Locked Account Owner Alias Show Actions" [ref=e580]:
                  - gridcell [ref=e581]
                  - gridcell "Select Item 2 Choose a Row" [ref=e585]:
                    - generic [ref=e586]:
                      - checkbox "Select Item 2 Choose a Row" [ref=e587]
                      - generic [ref=e590]: Select Item 2
                  - rowheader "Test_Account Edit Account Name" [ref=e591]:
                    - generic [ref=e592]:
                      - link "Test_Account" [ref=e598] [cursor=pointer]:
                        - /url: /lightning/r/001gL000014CjBUQA0/view
                        - generic [ref=e599]: Test_Account
                      - button "Edit Account Name" [ref=e600] [cursor=pointer]:
                        - img [ref=e601]
                  - gridcell "Edit Account Site" [ref=e604]:
                    - button "Edit Account Site" [ref=e606] [cursor=pointer]:
                      - img [ref=e607]
                  - gridcell "Edit Phone" [ref=e610]:
                    - button "Edit Phone" [ref=e612] [cursor=pointer]:
                      - img [ref=e613]
                  - gridcell "smana Locked Account Owner Alias" [ref=e616]:
                    - generic [ref=e617]:
                      - link "smana" [ref=e622] [cursor=pointer]:
                        - /url: /lightning/r/005gL00000GA3hlQAD/view
                        - generic [ref=e623]: smana
                      - img "Locked Account Owner Alias" [ref=e624]:
                        - img [ref=e625]
                  - gridcell "Show Actions" [ref=e628]:
                    - button "Show Actions" [ref=e634] [cursor=pointer]:
                      - img [ref=e636]
                      - generic [ref=e639]: Show Actions
                - row "Select Item 3 Choose a Row Test_Account Edit Account Name Edit Account Site Edit Phone smana Locked Account Owner Alias Show Actions" [ref=e640]:
                  - gridcell [ref=e641]
                  - gridcell "Select Item 3 Choose a Row" [ref=e645]:
                    - generic [ref=e646]:
                      - checkbox "Select Item 3 Choose a Row" [ref=e647]
                      - generic [ref=e650]: Select Item 3
                  - rowheader "Test_Account Edit Account Name" [ref=e651]:
                    - generic [ref=e652]:
                      - link "Test_Account" [ref=e658] [cursor=pointer]:
                        - /url: /lightning/r/001gL0000161UukQAE/view
                        - generic [ref=e659]: Test_Account
                      - button "Edit Account Name" [ref=e660] [cursor=pointer]:
                        - img [ref=e661]
                  - gridcell "Edit Account Site" [ref=e664]:
                    - button "Edit Account Site" [ref=e666] [cursor=pointer]:
                      - img [ref=e667]
                  - gridcell "Edit Phone" [ref=e670]:
                    - button "Edit Phone" [ref=e672] [cursor=pointer]:
                      - img [ref=e673]
                  - gridcell "smana Locked Account Owner Alias" [ref=e676]:
                    - generic [ref=e677]:
                      - link "smana" [ref=e682] [cursor=pointer]:
                        - /url: /lightning/r/005gL00000GA3hlQAD/view
                        - generic [ref=e683]: smana
                      - img "Locked Account Owner Alias" [ref=e684]:
                        - img [ref=e685]
                  - gridcell "Show Actions" [ref=e688]:
                    - button "Show Actions" [ref=e694] [cursor=pointer]:
                      - img [ref=e696]
                      - generic [ref=e699]: Show Actions
                - row "Select Item 4 Choose a Row Test_Account Edit Account Name Edit Account Site Edit Phone suj Locked Account Owner Alias Show Actions" [ref=e700]:
                  - gridcell [ref=e701]
                  - gridcell "Select Item 4 Choose a Row" [ref=e705]:
                    - generic [ref=e706]:
                      - checkbox "Select Item 4 Choose a Row" [ref=e707]
                      - generic [ref=e710]: Select Item 4
                  - rowheader "Test_Account Edit Account Name" [ref=e711]:
                    - generic [ref=e712]:
                      - link "Test_Account" [ref=e718] [cursor=pointer]:
                        - /url: /lightning/r/001gL000014CugMQAS/view
                        - generic [ref=e719]: Test_Account
                      - button "Edit Account Name" [ref=e720] [cursor=pointer]:
                        - img [ref=e721]
                  - gridcell "Edit Account Site" [ref=e724]:
                    - button "Edit Account Site" [ref=e726] [cursor=pointer]:
                      - img [ref=e727]
                  - gridcell "Edit Phone" [ref=e730]:
                    - button "Edit Phone" [ref=e732] [cursor=pointer]:
                      - img [ref=e733]
                  - gridcell "suj Locked Account Owner Alias" [ref=e736]:
                    - generic [ref=e737]:
                      - link "suj" [ref=e742] [cursor=pointer]:
                        - /url: /lightning/r/005gL00000FABtiQAH/view
                        - generic [ref=e743]: suj
                      - img "Locked Account Owner Alias" [ref=e744]:
                        - img [ref=e745]
                  - gridcell "Show Actions" [ref=e748]:
                    - button "Show Actions" [ref=e754] [cursor=pointer]:
                      - img [ref=e756]
                      - generic [ref=e759]: Show Actions
    - generic:
      - contentinfo "Utility Bar":
        - list [ref=e763]:
          - listitem [ref=e764]:
            - button "To Do List" [ref=e767] [cursor=pointer]:
              - img [ref=e771]
              - generic [ref=e774]: To Do List
  - generic:
    - status
```

# Test source

```ts
  1   | import { type Page, TestInfo } from '@playwright/test';
  2   | // import { test } from '@playwright/test';
  3   | 
  4   | /**
  5   |  * Default navigation timeout (ms).
  6   |  */
  7   | const DEFAULT_WAIT_TIME = 90_000;
  8   | 
  9   | /**
  10  |  * Base Page
  11  |  *
  12  |  * Abstract base class for all Page Objects in the framework.
  13  |  * Provides navigation and step-based execution patterns.
  14  |  *
  15  |  * @example
  16  |  * ```ts
  17  |  * class LoginPage extends BasePage {
  18  |  *   readonly pageName = 'LoginPage';
  19  |  *   protected readonly relativeUrl = '/login';
  20  |  *
  21  |  *   constructor(page: Page, baseUrl: string) {
  22  |  *     super(page, baseUrl);
  23  |  *   }
  24  |  *
  25  |  *   async login(username: string, password: string): Promise<void> {
  26  |  *     await this.step('Enter credentials and submit', async () => {
  27  |  *       await this.page.fill('#username', username);
  28  |  *       await this.page.fill('#password', password);
  29  |  *       await this.page.click('#submit');
  30  |  *     });
  31  |  *   }
  32  |  * }
  33  |  * ```
  34  |  */
  35  | export abstract class BasePage {
  36  |   protected readonly page: Page;
  37  |   protected readonly baseUrl: string;
  38  | 
  39  |   /** Human-readable name for this page */
  40  |   abstract readonly pageName: string;
  41  | 
  42  |   /** Relative URL path for this page (e.g. '/login') */
  43  |   protected abstract readonly relativeUrl: string;
  44  | 
  45  |   /** Full page URL (baseUrl + relativeUrl) */
  46  |   get pageUrl(): string {
  47  |     return `${this.baseUrl}${this.relativeUrl}`;
  48  |   }
  49  | 
  50  |   constructor(page: Page, baseUrl: string) {
  51  |     this.page = page;
  52  |     this.baseUrl = baseUrl;
  53  |   }
  54  | 
  55  |   /**
  56  |    * Navigate to this page using the default timeout.
  57  |    */
  58  |   async navigate(): Promise<void> {
  59  |     await this.page.goto(this.pageUrl, { timeout: DEFAULT_WAIT_TIME });
  60  |   }
  61  | 
  62  |   /**
  63  |    * Navigate to this page with a custom timeout.
  64  |    * @param waitTime - Timeout in milliseconds
  65  |    */
  66  |   async navigateWithTimeout(waitTime: number): Promise<void> {
  67  |     await this.page.goto(this.pageUrl, { timeout: waitTime });
  68  |   }
  69  | 
  70  |   /**
  71  |    * Execute a named step.
  72  |    *
  73  |    * @param description - Human-readable step description
  74  |    * @param action - Async action to execute within the step
  75  |    */
  76  |   protected async testStep(description: string, action: () => Promise<void>): Promise<void> {
  77  |     // Note: Playwright's test.step is commented out here to avoid double import error in consuming project. Agent should impelement a similar step wrapper in the actual Basepage implementation.
  78  |     // await test.step(`${this.pageName}: ${description}`, async () => {
  79  |     //   await action();
  80  |     // });
  81  |   }
  82  | 
  83  |   /**
  84  |    * Capture a screenshot and attach it to the Playwright test report.
  85  |    *
  86  |    * @param page - Playwright Page object
  87  |    * @param testInfo - Playwright TestInfo object
  88  |    * @param name - Descriptive name to hint the context of the screenshot
  89  |    */
  90  |   async captureScreenshot(page: Page, testInfo: TestInfo, name: string): Promise<void> {
> 91  |   const screenshot = await page.screenshot({ fullPage: true });
      |                                 ^ Error: page.screenshot: Target page, context or browser has been closed
  92  |   await testInfo.attach(
  93  |     name, 
  94  |     { 
  95  |       body: screenshot, 
  96  |       contentType: 'image/png' 
  97  |     });
  98  |   }
  99  | }
  100 | 
```
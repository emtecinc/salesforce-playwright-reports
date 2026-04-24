# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: account/change-account-owner-impersonation.spec.ts >> Account Owner Change - Impersonation and Ownership Transfer >> should change account owner via user impersonation and verify ownership transfer
- Location: tests/account/change-account-owner-impersonation.spec.ts:65:7

# Error details

```
TypeError: url.match is not a function
```

# Page snapshot

```yaml
- generic:
  - generic [ref=e2]:
    - generic [ref=e3]:
      - link "Skip to Navigation" [ref=e4] [cursor=pointer]:
        - /url: javascript:void(0);
      - link "Skip to Main Content" [ref=e5] [cursor=pointer]:
        - /url: javascript:void(0);
      - generic [ref=e9]:
        - generic [ref=e13]:
          - button "Toggle Panel" [ref=e17] [cursor=pointer]:
            - img [ref=e21]
            - generic [ref=e24]: Menu
          - generic [ref=e29]:
            - img [ref=e33]
            - generic [ref=e36]: Developer Edition
        - button "Show menu" [ref=e45] [cursor=pointer]:
          - img [ref=e47]
          - generic [ref=e50]: Show menu
      - generic [ref=e51]:
        - button "Search" [ref=e57]:
          - img [ref=e59]
          - text: Search...
        - navigation "Global Header" [ref=e62]:
          - list [ref=e64]:
            - listitem [ref=e65]:
              - group [ref=e66]:
                - button "Add favorite" [ref=e68] [cursor=pointer]:
                  - generic [ref=e69]:
                    - img [ref=e73]
                    - tooltip "Add favorite"
                - button "Favorites list" [ref=e77] [cursor=pointer]:
                  - generic [ref=e78]:
                    - img [ref=e82]
                    - tooltip "Favorites list"
            - listitem [ref=e85]:
              - button "Global Actions" [ref=e91] [cursor=pointer]:
                - generic [ref=e92]:
                  - img [ref=e96]
                  - tooltip "Global Actions"
            - listitem [ref=e99]:
              - button "Guidance Center" [ref=e101] [cursor=pointer]:
                - generic [ref=e102]:
                  - img [ref=e106]
                  - tooltip "Guidance Center"
            - listitem [ref=e109]:
              - button "Salesforce Help" [ref=e112] [cursor=pointer]:
                - generic [ref=e113]:
                  - img [ref=e117]
                  - tooltip "Salesforce Help"
            - listitem [ref=e120]:
              - button "Setup" [ref=e126] [cursor=pointer]:
                - generic [ref=e127]:
                  - img [ref=e131]
                  - tooltip "Setup"
            - listitem [ref=e134]:
              - button "Notifications" [ref=e137] [cursor=pointer]:
                - generic [ref=e138]:
                  - img [ref=e143]
                  - tooltip "Notifications"
            - listitem [ref=e147]:
              - button "View profile" [ref=e150] [cursor=pointer]:
                - generic [ref=e151]:
                  - tooltip "View profile"
    - generic [ref=e155]:
      - generic [ref=e158]:
        - generic [ref=e160]:
          - navigation "App" [ref=e161]:
            - button "App Launcher" [ref=e163] [cursor=pointer]:
              - generic [ref=e174]: App Launcher
          - heading "Sales" [level=1] [ref=e175]:
            - generic "Sales" [ref=e176]
        - navigation "Global" [ref=e179]:
          - list [ref=e180]:
            - listitem [ref=e181]:
              - link "Home" [ref=e182] [cursor=pointer]:
                - /url: /lightning/page/home
                - generic [ref=e183]: Home
            - listitem [ref=e184]:
              - link "Opportunities" [ref=e185] [cursor=pointer]:
                - /url: /lightning/o/Opportunity/home
                - generic [ref=e186]: Opportunities
              - button "Opportunities List" [ref=e190] [cursor=pointer]:
                - img [ref=e194]
                - generic [ref=e197]: Opportunities List
            - listitem [ref=e198]:
              - link "Leads" [ref=e199] [cursor=pointer]:
                - /url: /lightning/o/Lead/home
                - generic [ref=e200]: Leads
              - button "Leads List" [ref=e204] [cursor=pointer]:
                - img [ref=e208]
                - generic [ref=e211]: Leads List
            - listitem [ref=e212]:
              - link "Tasks" [ref=e213] [cursor=pointer]:
                - /url: /lightning/o/Task/home
                - generic [ref=e214]: Tasks
              - button "Tasks List" [ref=e218] [cursor=pointer]:
                - img [ref=e222]
                - generic [ref=e225]: Tasks List
            - listitem [ref=e226]:
              - link "Files" [ref=e227] [cursor=pointer]:
                - /url: /lightning/o/ContentDocument/home
                - generic [ref=e228]: Files
              - button "Files List" [ref=e232] [cursor=pointer]:
                - img [ref=e236]
                - generic [ref=e239]: Files List
            - listitem [ref=e240] [cursor=pointer]:
              - link "Accounts" [ref=e241]:
                - /url: /lightning/o/Account/home
                - generic [ref=e242]: Accounts
              - button "Accounts List" [ref=e246]:
                - img [ref=e250]
                - generic [ref=e253]: Accounts List
            - listitem [ref=e254]:
              - link "Contacts" [ref=e255] [cursor=pointer]:
                - /url: /lightning/o/Contact/home
                - generic [ref=e256]: Contacts
              - button "Contacts List" [ref=e260] [cursor=pointer]:
                - img [ref=e264]
                - generic [ref=e267]: Contacts List
            - listitem [ref=e268]:
              - link "Campaigns" [ref=e269] [cursor=pointer]:
                - /url: /lightning/o/Campaign/home
                - generic [ref=e270]: Campaigns
              - button "Campaigns List" [ref=e274] [cursor=pointer]:
                - img [ref=e278]
                - generic [ref=e281]: Campaigns List
            - listitem [ref=e282]:
              - link "Dashboards" [ref=e283] [cursor=pointer]:
                - /url: /lightning/o/Dashboard/home
                - generic [ref=e284]: Dashboards
              - button "Dashboards List" [ref=e288] [cursor=pointer]:
                - img [ref=e292]
                - generic [ref=e295]: Dashboards List
            - listitem [ref=e296]:
              - link "Reports" [ref=e297] [cursor=pointer]:
                - /url: /lightning/o/Report/home
                - generic [ref=e298]: Reports
              - button "Reports List" [ref=e302] [cursor=pointer]:
                - img [ref=e306]
                - generic [ref=e309]: Reports List
            - listitem [ref=e310]:
              - button "Show more navigation items" [ref=e312] [cursor=pointer]:
                - generic [ref=e313]: More
                - img [ref=e317]
                - generic [ref=e320]: Show more navigation items
            - listitem [ref=e321]:
              - button "Edit nav items" [ref=e323] [cursor=pointer]:
                - img [ref=e325]
                - generic [ref=e328]: Edit nav items
      - main [ref=e330]:
        - generic [ref=e346]:
          - generic [ref=e355]:
            - generic [ref=e356]:
              - generic [ref=e357]:
                - heading "Account Test_Account_1777029137533" [level=1] [ref=e367]:
                  - generic [ref=e369]: Account
                  - generic [ref=e370]: Test_Account_1777029137533
                - button "View Account Hierarchy" [ref=e381] [cursor=pointer]:
                  - img [ref=e383]
                  - generic [ref=e386]: View Account Hierarchy
              - button "Follow" [ref=e391] [cursor=pointer]:
                - generic [ref=e392]:
                  - img [ref=e396]
                  - text: Follow
              - generic [ref=e401]:
                - generic "New Contact" [ref=e402]:
                  - button "New Contact" [ref=e407] [cursor=pointer]
                - generic "New Case" [ref=e408]:
                  - button "New Case" [ref=e413] [cursor=pointer]
                - generic "New Note" [ref=e414]:
                  - button "New Note" [ref=e419] [cursor=pointer]
                - button "Show more actions" [ref=e421] [cursor=pointer]:
                  - img [ref=e423]
                  - generic [ref=e426]: Show more actions
            - generic [ref=e427]:
              - generic [ref=e429]:
                - paragraph [ref=e430]: Type
                - paragraph
              - generic [ref=e432]:
                - paragraph [ref=e433]: Phone
                - paragraph
              - generic [ref=e435]:
                - paragraph [ref=e436]: Website
                - paragraph
              - generic [ref=e438]:
                - paragraph [ref=e439]: Account Owner
                - paragraph [ref=e440]:
                  - generic [ref=e443]:
                    - generic [ref=e450]:
                      - link "Sujitkumar Gaikwad" [ref=e451] [cursor=pointer]:
                        - /url: /lightning/r/User/005gL00000FABtiQAH/view
                        - generic [ref=e455]: Sujitkumar Gaikwad
                      - button "Open Sujitkumar Gaikwad Preview" [ref=e457] [cursor=pointer]:
                        - img [ref=e459]
                        - generic [ref=e462]: Open Sujitkumar Gaikwad Preview
                    - button "Change Owner" [ref=e464] [cursor=pointer]:
                      - img [ref=e466]
                      - generic [ref=e469]: Change Owner
              - generic [ref=e471]:
                - paragraph [ref=e472]: Account Site
                - paragraph
              - generic [ref=e474]:
                - paragraph [ref=e475]: Industry
                - paragraph
          - generic [ref=e477]:
            - generic [ref=e483]:
              - heading "Tabs" [level=2] [ref=e484]
              - generic "Tabs" [ref=e485]:
                - generic [ref=e486]:
                  - heading "Tabs" [level=2] [ref=e487]
                  - tablist "Tabs" [ref=e489]:
                    - tab "Related" [selected] [ref=e490] [cursor=pointer]
                    - tab "Details" [ref=e491] [cursor=pointer]
                  - tabpanel "Related" [ref=e494]:
                    - generic [ref=e495]:
                      - article [ref=e500]:
                        - generic [ref=e502]:
                          - img [ref=e507]
                          - heading "We found no potential duplicates of this Account." [level=2] [ref=e511]:
                            - generic "We found no potential duplicates of this Account." [ref=e512]
                      - generic [ref=e516]:
                        - article "Contacts" [ref=e522]:
                          - generic [ref=e527]:
                            - generic [ref=e529]:
                              - img [ref=e533]
                              - heading "Contacts (0)" [level=2] [ref=e535]:
                                - link "Contacts (0)" [ref=e536] [cursor=pointer]:
                                  - /url: /lightning/r/Account/001gL000016f9Y3QAI/related/Contacts/view
                                  - generic "Contacts" [ref=e537]
                                  - generic "(0)" [ref=e538]
                            - generic "New" [ref=e542]:
                              - button "New" [ref=e547] [cursor=pointer]
                        - article "Opportunities" [ref=e553]:
                          - generic [ref=e558]:
                            - generic [ref=e560]:
                              - img [ref=e564]
                              - heading "Opportunities (0)" [level=2] [ref=e566]:
                                - link "Opportunities (0)" [ref=e567] [cursor=pointer]:
                                  - /url: /lightning/r/Account/001gL000016f9Y3QAI/related/Opportunities/view
                                  - generic "Opportunities" [ref=e568]
                                  - generic "(0)" [ref=e569]
                            - generic "New" [ref=e573]:
                              - button "New" [ref=e578] [cursor=pointer]
                        - article "Cases" [ref=e584]:
                          - generic [ref=e589]:
                            - generic [ref=e591]:
                              - img [ref=e595]
                              - heading "Cases (0)" [level=2] [ref=e597]:
                                - link "Cases (0)" [ref=e598] [cursor=pointer]:
                                  - /url: /lightning/r/Account/001gL000016f9Y3QAI/related/Cases/view
                                  - generic "Cases" [ref=e599]
                                  - generic "(0)" [ref=e600]
                            - generic "New" [ref=e604]:
                              - button "New" [ref=e609] [cursor=pointer]
                        - article [ref=e616]:
                          - generic [ref=e617]:
                            - img [ref=e619]
                            - heading "Notes & Attachments" [level=2] [ref=e620]
                        - article [ref=e627]:
                          - generic [ref=e628]:
                            - img [ref=e630]
                            - heading "Partners" [level=2] [ref=e631]
            - generic [ref=e638]:
              - heading "Tabs" [level=2] [ref=e639]
              - generic "Tabs" [ref=e640]:
                - generic [ref=e641]:
                  - heading "Tabs" [level=2] [ref=e642]
                  - tablist "Tabs" [ref=e644]:
                    - tab "Activity" [selected] [ref=e645] [cursor=pointer]
                    - tab "Chatter" [ref=e646] [cursor=pointer]
                  - tabpanel "Activity" [ref=e649]:
                    - generic [ref=e655]:
                      - heading "Activity Publisher" [level=2] [ref=e656]
                      - generic [ref=e657]:
                        - group [ref=e658]:
                          - generic [ref=e660]:
                            - button "New Task" [ref=e661] [cursor=pointer]:
                              - generic [ref=e663]:
                                - img [ref=e665]
                                - generic [ref=e668]: New Task
                              - generic: New Task
                            - generic [ref=e669]:
                              - button "No Additional New Task Actions" [disabled]:
                                - generic:
                                  - img
                                - generic: No Additional New Task Actions
                        - group [ref=e670]:
                          - generic [ref=e672]:
                            - button "Log a Call" [ref=e673] [cursor=pointer]:
                              - generic [ref=e675]:
                                - img [ref=e677]
                                - generic [ref=e680]: Log a Call
                              - generic: Log a Call
                            - button "More Log a Call Actions" [ref=e682] [cursor=pointer]:
                              - img [ref=e684]
                              - generic [ref=e687]: More Log a Call Actions
                        - group [ref=e688]:
                          - generic [ref=e690]:
                            - button "New Event" [ref=e691] [cursor=pointer]:
                              - generic [ref=e693]:
                                - img [ref=e695]
                                - generic [ref=e698]: New Event
                              - generic: New Event
                            - button "More New Event Actions" [ref=e700] [cursor=pointer]:
                              - img [ref=e702]
                              - generic [ref=e705]: More New Event Actions
                        - group [ref=e706]:
                          - generic [ref=e708]:
                            - button "Email" [ref=e709] [cursor=pointer]:
                              - generic [ref=e711]:
                                - img [ref=e713]
                                - generic [ref=e716]: Email
                              - generic: Email
                            - button "More Email Actions" [ref=e718] [cursor=pointer]:
                              - img [ref=e720]
                              - generic [ref=e723]: More Email Actions
                      - heading "Activity Timeline" [level=2] [ref=e724]
                      - generic [ref=e726]:
                        - link "Skip to the bottom of the activity timeline" [ref=e727] [cursor=pointer]:
                          - /url: javascript:void(0);
                        - generic [ref=e729]:
                          - generic [ref=e731]: "Filters: All time • All activities • All types"
                          - button "Timeline Settings" [ref=e732] [cursor=pointer]:
                            - img [ref=e734]
                            - generic [ref=e737]: Timeline Settings
                        - generic [ref=e740]:
                          - button "Refresh" [ref=e741] [cursor=pointer]
                          - text: •
                          - button "Expand All. Show details for activities in the timeline." [ref=e742] [cursor=pointer]: Expand All
                          - text: •
                          - button "View All" [ref=e743] [cursor=pointer]
                        - generic [ref=e745]:
                          - heading "Upcoming & Overdue" [level=3] [ref=e746]:
                            - button "Upcoming & Overdue" [expanded] [ref=e747] [cursor=pointer]:
                              - img [ref=e749]
                              - text: Upcoming & Overdue
                          - generic [ref=e752]:
                            - generic:
                              - list
                            - generic [ref=e755]:
                              - text: No activities to show.
                              - text: Get started by sending an email, scheduling a task, and more.
                        - status [ref=e756]:
                          - generic [ref=e758]:
                            - img [ref=e762]
                            - generic [ref=e765]: information
                          - paragraph [ref=e767]: To change what's shown, try changing your filters.
                        - button "Show All Activities" [ref=e769] [cursor=pointer]
                        - link "Skip to the top of the activity timeline" [ref=e770] [cursor=pointer]:
                          - /url: javascript:void(0);
    - generic:
      - contentinfo "Utility Bar":
        - list [ref=e775]:
          - listitem [ref=e776]:
            - button "To Do List" [ref=e779] [cursor=pointer]:
              - img [ref=e783]
              - generic [ref=e786]: To Do List
  - generic:
    - generic [ref=e789]:
      - generic [ref=e791]:
        - img [ref=e793]
        - generic [ref=e796]: Success notification.
      - generic [ref=e797]:
        - generic [ref=e800]:
          - text: Account "
          - link "Test_Account_1777029137533" [ref=e801] [cursor=pointer]:
            - /url: javascript:void(0)
            - generic [ref=e802]: Test_Account_1777029137533
          - text: "\" was created."
        - generic [ref=e803]: Press Control + F6 to navigate to the next toast notification or focusable region.
      - button "Close" [ref=e805] [cursor=pointer]:
        - img [ref=e809]
        - generic [ref=e812]: Close
    - status [ref=e813]: Success notification.Account "Test_Account_1777029137533" was created. Press Control + F6 to navigate to the next toast notification or focusable region.
```

# Test source

```ts
  148 |         throw new Error(`Record not found for ${sObject} where ${fieldName}='${value}'`);
  149 |     }
  150 | 
  151 |     /**
  152 |      * Manual registration for records created via UI.
  153 |      */
  154 |     registerForCleanup(sObject: string, id: string, name?: string): void {
  155 |         // Avoid duplicate registrations for the same record
  156 |         const alreadyRegistered = this.recordsToCleanup.some(
  157 |             (r) => r.id === id && r.type === sObject
  158 |         );
  159 |         if (alreadyRegistered) {
  160 |             console.log(`⏭️  Already registered for cleanup: ${sObject} (${id})`);
  161 |             return;
  162 |         }
  163 |         this.recordsToCleanup.push({ type: sObject, id, name });
  164 |         console.log(
  165 |             `📌 Registered for cleanup: ${sObject} (${id})${name ? ` - ${name}` : ''}`
  166 |         );
  167 |     }
  168 | 
  169 |     /**
  170 |      * Deletes all registered records in REVERSE order.
  171 |      * This ensures child records are deleted before parents.
  172 |      * This method ALWAYS runs in afterAll/afterEach, regardless of test pass/fail.
  173 |      *
  174 |      * Cleanup is automatic in test automation — no opt-in required.
  175 |      */
  176 |     async teardown(): Promise<void> {
  177 |         if (this.recordsToCleanup.length === 0) {
  178 |             console.log('✅ No records to clean up');
  179 |             return;
  180 |         }
  181 | 
  182 |         console.log(
  183 |             `\n🧹 Starting automatic cleanup of ${this.recordsToCleanup.length} records...`
  184 |         );
  185 |         console.log('   (Cleanup runs regardless of test pass/fail)\n');
  186 | 
  187 |         let successCount = 0;
  188 |         let failCount = 0;
  189 | 
  190 |         for (const record of this.recordsToCleanup.reverse()) {
  191 |             try {
  192 |                 const response = await fetch(
  193 |                     `${this.instanceUrl}/services/data/v65.0/sobjects/${record.type}/${record.id}`,
  194 |                     {
  195 |                         method: 'DELETE',
  196 |                         headers: { Authorization: `Bearer ${this.accessToken}` },
  197 |                     }
  198 |                 );
  199 | 
  200 |                 if (response.ok || response.status === 404) {
  201 |                     console.log(
  202 |                         `✅ Deleted ${record.type}: ${record.id}${record.name ? ` - ${record.name}` : ''}`
  203 |                     );
  204 |                     successCount++;
  205 |                 } else {
  206 |                     const error = await response.text();
  207 |                     console.error(
  208 |                         `❌ Failed to delete ${record.type} ${record.id}: ${error}`
  209 |                     );
  210 |                     failCount++;
  211 |                 }
  212 |             } catch (error) {
  213 |                 console.error(
  214 |                     `❌ Exception deleting ${record.type} ${record.id}:`,
  215 |                     error
  216 |                 );
  217 |                 failCount++;
  218 |             }
  219 |         }
  220 | 
  221 |         this.recordsToCleanup = [];
  222 |         console.log(
  223 |             `\n✅ Cleanup completed: ${successCount} deleted, ${failCount} failed\n`
  224 |         );
  225 |     }
  226 | 
  227 |     /**
  228 |      * Extract recordId and objectApiName from a Salesforce record page URL
  229 |      * and register the record for cleanup.
  230 |      *
  231 |      * Use this when record creation redirects to the record's detail page.
  232 |      * URL format: /lightning/r/<ObjectName>/<RecordId>/view
  233 |      *
  234 |      * @param url - Full page URL (e.g., from `page.url()`)
  235 |      * @param name - Optional display name for logging
  236 |      * @returns Object with `objectApiName` and `recordId`
  237 |      * @throws Error if URL does not match Salesforce record page pattern
  238 |      *
  239 |      * @example
  240 |      * ```ts
  241 |      * const { objectApiName, recordId } = dataFactory.registerRecordFromUrl(page.url(), 'My Opportunity');
  242 |      * ```
  243 |      */
  244 |     registerRecordFromUrl(
  245 |         url: string,
  246 |         name?: string,
  247 |     ): { objectApiName: string; recordId: string } {
> 248 |         const match = url.match(/\/lightning\/r\/([A-Za-z_][A-Za-z0-9_]*)\/([a-zA-Z0-9]{15,18})\/view/);
      |                           ^ TypeError: url.match is not a function
  249 |         if (!match) {
  250 |             throw new Error(
  251 |                 `Cannot extract record info from URL: ${url}. Expected format: /lightning/r/<Object>/<RecordId>/view`,
  252 |             );
  253 |         }
  254 | 
  255 |         const objectApiName = match[1];
  256 |         console.log("ObjectName: ", objectApiName);
  257 |         const recordId = match[2];
  258 |         console.log("RecordId: ", recordId);
  259 | 
  260 |         this.registerForCleanup(objectApiName, recordId, name);
  261 |         return { objectApiName, recordId };
  262 |     }
  263 | 
  264 |     /**
  265 |      * Create a record in Salesforce via REST API.
  266 |      * Automatically registers the created record for cleanup.
  267 |      *
  268 |      * @param sObject - Salesforce object API name (e.g., 'Account', 'Contact', 'Lead')
  269 |      * @param payload - Record field data as a plain object
  270 |      * @param autoRegister - Automatically register for cleanup (default: true)
  271 |      * @returns The created record ID
  272 |      *
  273 |      * @example
  274 |      * ```ts
  275 |      * const payload = PayloadBuilder
  276 |      *   .fromFile('test-data/api/account-template.json')
  277 |      *   .set('Name', TestDataGenerator.uniqueName('Account'))
  278 |      *   .build();
  279 |      *
  280 |      * const accountId = await dataFactory.createRecord('Account', payload);
  281 |      * ```
  282 |      */
  283 |     async createRecord(
  284 |         sObject: string,
  285 |         payload: Record<string, unknown>,
  286 |         autoRegister: boolean = true
  287 |     ): Promise<string> {
  288 |         // await this.authenticate();
  289 | 
  290 |         const response = await fetch(
  291 |             `${this.instanceUrl}/services/data/v65.0/sobjects/${sObject}`,
  292 |             {
  293 |                 method: 'POST',
  294 |                 headers: {
  295 |                     Authorization: `Bearer ${this.accessToken}`,
  296 |                     'Content-Type': 'application/json',
  297 |                     // Bypass Salesforce duplicate rules for test data creation
  298 |                     'Sforce-Duplicate-Rule-Header': 'allowSave=true',
  299 |                 },
  300 |                 body: JSON.stringify(payload),
  301 |             }
  302 |         );
  303 | 
  304 |         const result = (await response.json()) as any;
  305 | 
  306 |         if (!response.ok) {
  307 |             const errors = result.errors || result;
  308 |             throw new Error(
  309 |                 `Failed to create ${sObject}: ${JSON.stringify(errors)}`
  310 |             );
  311 |         }
  312 | 
  313 |         const recordId = result.id;
  314 |         const recordName =
  315 |             (payload.Name as string) ||
  316 |             (payload.LastName as string) ||
  317 |             (payload.Subject as string) ||
  318 |             recordId;
  319 | 
  320 |         console.log(`✅ Created ${sObject} via API: ${recordId} - ${recordName}`);
  321 | 
  322 |         if (autoRegister) {
  323 |             this.registerForCleanup(sObject, recordId, recordName);
  324 |         }
  325 | 
  326 |         return recordId;
  327 |     }
  328 | 
  329 |     /**
  330 |      * Update an existing record in Salesforce via REST API (PATCH).
  331 |      * Supports partial updates — only the fields in the payload are changed.
  332 |      *
  333 |      * @param sObject - Salesforce object API name (e.g., 'Account', 'Contact')
  334 |      * @param recordId - The 15 or 18 character Salesforce record ID
  335 |      * @param payload - Fields to update (only changed fields are required)
  336 |      * @returns void — throws on failure
  337 |      *
  338 |      * @example
  339 |      * ```ts
  340 |      * await dataFactory.updateRecord('Contact', contactId, {
  341 |      *   Title: 'Senior QA Engineer',
  342 |      *   Department: 'Quality Assurance',
  343 |      * });
  344 |      * ```
  345 |      */
  346 |     async updateRecord(
  347 |         sObject: string,
  348 |         recordId: string,
```
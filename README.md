# Zendesk (zendesk)

Zendesk provides customer service and engagement software that helps businesses manage support tickets, automate workflows, and offer multi-channel supportincluding email, chat, social media, and phonethrough a unified platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zendesk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zendesk/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Chat
- CRM
- Help Center
- Sell
- Support
- T1
- Talk
- Ticketing
- Tickets

## Timestamps

- **Created:** Tue Jan 07 2025 19:00:00 GMT-0500 (Eastern Standard Time)
- **Modified:** 2026-05-19

## APIs

### Zendesk Assignables API

The Zendesk Assignables API lets you find out who or what can be assigned to a piece of worktypically a ticketgiven your accounts permissions, groups, and routing rules. It returns the set of eligible assignees (such as agents or groups) for a particular context, so you can build assignee pickers in custom apps, validate that an assignment is allowed before updating a ticket, or automate routing workflows.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/introduction/](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Assignables

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- [OpenAPI](openapi/assignables-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Target Type API

The Zendesk Target Types API exposes a catalog of the legacy target integrations your Zendesk account supportssuch as email or HTTP/URL targetsthat triggers and automations can use to send notifications or payloads to external systems. Its primarily a discovery endpoint: it lets you list the available target types and see the fields each one requires, so you can correctly create target instances with the Targets API.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/targets/targets/](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Target Types

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- [OpenAPI](openapi/target-type-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Account API

The Zendesk Account API lets you programmatically work with account-level records and settings so you can keep Zendesk in sync with the rest of your stack. In Zendesk Sell, it exposes endpoints to list, retrieve, create, update, and delete account objects (the companies you do business with), manage custom fields and tags, and relate accounts to contacts and deals, with search, filtering, and pagination for efficient data access.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/account/](https://developer.zendesk.com/api-reference/sales-crm/resources/account/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- Accounts

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/account/)
- [OpenAPI](openapi/account-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Accounts API

The Zendesk Sell Accounts API lets you programmatically manage the company records (accounts) in your CRM. It provides REST endpoints to create, read, update, and delete accounts; search and filter them; and work with related data such as associated contacts, deals, activities, notes, tags, and custom fields.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/account/](https://developer.zendesk.com/api-reference/sales-crm/resources/account/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- Accounts

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/account/)
- [OpenAPI](openapi/accounts-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Activities API

The Zendesk Sell Activities API lets you programmatically manage the work your sales team doessuch as calls, emails, meetings, and tasksby creating, reading, updating, and deleting activity records. Activities can be linked to leads, contacts, and deals, include details like due dates, reminders, outcomes, owners, and notes, and can be filtered and paginated by type, status, user, or timeframe.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/activity_stream/](https://developer.zendesk.com/api-reference/ticketing/tickets/activity_stream/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Activities

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/activity_stream/)
- [OpenAPI](openapi/activities-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Any Channel API

The Zendesk Any Channel API (also called the Channel Framework) lets developers turn virtually any external communication sourcemessaging apps, social networks, SMS gateways, custom apps, or other platformsinto a firstclass Zendesk channel.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Channels

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/)
- [OpenAPI](openapi/any-channel-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Approval Workflow Instances API

The Zendesk Approval Workflow Instances API lets you programmatically start, track, and manage approvals that are built with Zendesks workflow tools. Using REST endpoints, you can create an instance of a predefined approval workflow, associate it with a record such as a ticket, pass input data, and then query the instance to monitor its current state and steps.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/introduction/](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Approvals
- Instances
- Workflows

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- [OpenAPI](openapi/approval-workflow-instances-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Attachments API

The Zendesk Attachments API lets you handle files that users add to Zendesk, primarily for ticket comments (and, via related endpoints, other content like help center articles). You upload a file to Zendesk storage to get an upload token, then reference that token when creating or updating a ticket comment so the file becomes an attachment.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Attachments

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/)
- [OpenAPI](openapi/attachments-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Audit Logs API

The Zendesk Audit Logs API lets you programmatically retrieve a chronological record of important administrative and security-related events in your Zendesk accountsuch as configuration changes, user and role updates, authentications, and other actions that affect account settings.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/audit_logs/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/audit_logs/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Audit Logs
- Audits

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/audit_logs/)
- [OpenAPI](openapi/audit-logs-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Autocomplete API

The Zendesk Autocomplete API provides fast, typeahead-style suggestions for common Zendesk resourcesmost notably users and organizationsso your app can quickly find matches as someone types. You send a partial query (like a name or email) and get back a small, relevance-ordered list of candidates, limited to fields you need (for example, id, name, email) and filtered by the requesters permissions.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Autocomplete

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- [OpenAPI](openapi/autocomplete-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Automations API

The Zendesk Automations API lets you programmatically manage time-based business rules that keep Support tickets moving without manual work. Automations evaluate ticket conditions on a regular schedule (typically hourly) using time metrics like hours since creation, last update, or status change, and then perform actions such as changing status or priority, reassigning, adding tags, or sending notifications.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/automations/](https://developer.zendesk.com/api-reference/ticketing/business-rules/automations/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Automations

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/automations/)
- [OpenAPI](openapi/automations-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Bookmarks API

The Zendesk Bookmarks API lets you programmatically manage an agents personal starred items in Zendesk, providing endpoints to list, create, and delete bookmarks. A bookmark is a lightweight record that points to another Zendesk resource (for example, something an agent wants quick access to in the interface), and its scoped to the user who created it. With the API you can fetch all of a users bookmarks, add new ones to surface important work, and remove those that are no longer relevant.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/bookmarks/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/bookmarks/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Bookmarks

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/bookmarks/)
- [OpenAPI](openapi/bookmarks-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Brand Agents API

The Zendesk Brand Agents API lets you programmatically manage which agents have access to which brands in a multibrand Zendesk Support account. It provides endpoints to list the agents associated with a given brand and to add or remove agents from that brand, so you can automate onboarding/offboarding, sync brand access from external directories, and enforce leastprivilege access at scale.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/brand_agents/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/brand_agents/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Brand Agents

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/brand_agents/)
- [OpenAPI](openapi/brand-agents-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Brands API

The Zendesk Brands API is part of the Zendesk Support API that lets you programmatically manage a multibrand setup. It provides endpoints to list, create, update, delete, and fetch the default brand, along with brand-specific settings used across the agent workspace, Help Center, and email.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/brands/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/brands/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Brands

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/brands/)
- [OpenAPI](openapi/brands-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Channels API

The Zendesk Channels API (Channel Framework) lets developers build custom integrations that bring messages from any external source into Zendesk and send agent replies back out to the original channel. With it, you can register and configure channel accounts, accept inbound messages and attachments, map senders to end users, create or update tickets/conversations, preserve threading and context with metadata, and use channelback to post agent replies to the thirdparty system.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Channels

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/channel_framework/)
- [OpenAPI](openapi/channels-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Chat File Redactions API

The Zendesk Chat File Redactions API lets administrators and trusted tools permanently remove files that were shared in live chat conversations. By redacting a file, its asset is taken out of circulation so it can no longer be downloaded or accessed via its URL, helping teams remediate accidental sharing of sensitive information and meet privacy or compliance requirements (for example, GDPR or CCPA).

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Chats
- Fiiles
- Redactions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- [OpenAPI](openapi/chat-file-redactions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Chat Redactions API

The Zendesk Chat Redactions API lets you programmatically remove sensitive information from chat transcripts and any shared files, so teams can meet security and privacy requirements without deleting entire conversations. You can target specific parts of a message (for example, a credit card number or password), redact an entire message, or remove an attachment; the change is permanent and designed to preserve the rest of the transcript and its metadata.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Chats
- Redactions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- [OpenAPI](openapi/chat-redactions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Comment Redactions API

The Zendesk Comment Redactions API lets you programmatically and permanently remove sensitive information from ticket conversations without deleting the entire message. By targeting a specific ticket comment and supplying the text to scrub (for example, credit card numbers, passwords, or PII), the API replaces the matching content in both the plain text and HTML versions with a redacted placeholder and records a redaction event in the tickets audit trail.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Comments
- Redactions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/)
- [OpenAPI](openapi/comment-redactions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Custom Objects API

The Zendesk Custom Objects API lets you model and store your own business datasuch as orders, subscriptions, devices, or contractsdirectly in Zendesk and relate it to native resources like tickets, users, and organizations. With it, you define object types and fields, create, read, update, and delete records, and establish one-to-one or one-to-many relationships so agents and workflows can access rich context in the Agent Workspace.

- **Human URL:** [https://developer.zendesk.com/api-reference/custom-data/introduction/](https://developer.zendesk.com/api-reference/custom-data/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Custom Objects

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/custom-data/introduction/)
- [OpenAPI](openapi/custom-objects-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Custom Roles API

The Zendesk Custom Roles API lets you programmatically manage the agent permission sets used in Zendesk Support (typically on Enterprise plans). Through it, you can list and fetch existing roles, create new ones, update their names, descriptions, and granular permissions, and delete roles you no longer need.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/custom_roles/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/custom_roles/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Custom Roles

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/custom_roles/)
- [OpenAPI](openapi/custom-roles-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Custom Status API

The Zendesk Custom Status API lets you programmatically manage the custom ticket statuses your account uses beyond the builtins. With it, you can list and retrieve statuses, create new ones, update labels and descriptions for agents and end users, localize translations, activate or deactivate statuses, and control their display order.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/](https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Custom Status

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/)
- [OpenAPI](openapi/custom-status-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Custom Statuses API

The Zendesk Custom Statuses API lets you programmatically create, read, update, delete, and reorder the custom ticket statuses your account uses, giving you more granular workflow states while still rolling up to Zendesks core status categories (like New, Open, Pending, On-hold, Solved, Closed) for SLAs and reporting.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/](https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Custom Statuses

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/custom_ticket_statuses/)
- [OpenAPI](openapi/custom-statuses-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Deleted Tickets API

The Zendesk Deleted Tickets API lets you manage tickets that have been soft-deleted in Zendesk Support. It provides endpoints to list and inspect deleted tickets, restore them to an active state if they were removed by mistake, or permanently delete them when you need to purge data. The API also supports bulk restore and bulk permanent deletion for handling many tickets at once.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Deleted Tickets
- Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- [OpenAPI](openapi/deleted-tickets-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Deleted Users API

The Zendesk Deleted Users API lets administrators manage users who have been soft-deleted in a Zendesk Support account. It provides endpoints to list and inspect deleted user records, restore a deleted user to an active state if the deletion was accidental, or permanently purge a user when you need to remove their personal data for compliance.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/users/users/](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Deleted Users
- Users

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- [OpenAPI](openapi/deleted-users-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Deletion Schedules API

The Zendesk Deletion Schedules API lets you programmatically plan and manage future-dated deletions of data in Zendesk to meet retention and privacy requirements (for example, GDPR/CCPA). Instead of deleting immediately, you create schedules that target specific records (such as user or ticket data), choose when the deletion should occur, and then monitor, update, or cancel those schedules before they run.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/deletion_schedules/](https://developer.zendesk.com/api-reference/ticketing/business-rules/deletion_schedules/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Deletion Schedules
- Schedules

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/deletion_schedules/)
- [OpenAPI](openapi/deletion-schedules-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Dynamic Content API

The Zendesk Dynamic Content API lets you manage reusable, localized text snippetscalled dynamic content itemsso you can keep messages consistent across macros, triggers, automations, email notifications, and apps. With it, you can programmatically create, read, update, and delete items; add and edit language variants; set a default locale; and activate or deactivate content.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/dynamic_content/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/dynamic_content/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Content
- Dynamic Content

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/dynamic_content/)
- [OpenAPI](openapi/dynamic-content-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Email Notifications API

The Zendesk Email Notifications API (in Zendesk Support) lets admins and developers programmatically inspect the outbound emails Zendesk sendssuch as ticket update notifications. It exposes searchable delivery logs and metadata for each message, including recipient, subject, timestamps, delivery status (for example delivered, deferred, bounced, or complaint) and failure reasons, plus identifiers that help trace which ticket or business rule triggered the email.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/email_notifications/](https://developer.zendesk.com/api-reference/ticketing/tickets/email_notifications/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Email
- Notifications

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/email_notifications/)
- [OpenAPI](openapi/email-notifications-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Group Memberships API

The Zendesk Group Memberships API lets you programmatically manage the relationship between users (typically agents) and groups in a Zendesk Support account. With it, you can list memberships across the account or scoped to a specific user or group, add a user to a group, remove a user from a group, and set which group is an agents default. Each membership ties a user_id to a group_id and can indicate the default group that agent belongs to, which affects ticket routing and workflows.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/groups/group_memberships/](https://developer.zendesk.com/api-reference/ticketing/groups/group_memberships/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Groups
- Memberships

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/groups/group_memberships/)
- [OpenAPI](openapi/group-memberships-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Group SLAs API

The Zendesk Group SLAs API lets you manage and report on service-level targets that are scoped to support groups, not just to tickets overall. With it, you can programmatically create and update SLA policies that define different reply and resolution time targets per group, determine which policy and targets are applied to a given ticket as it moves between groups, and retrieve timing details such as remaining time, breach status, and pauses.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/group_sla_policies/](https://developer.zendesk.com/api-reference/ticketing/business-rules/group_sla_policies/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Groups
- Service Level Agreements
- SLA

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/group_sla_policies/)
- [OpenAPI](openapi/group-slas-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Groups API

The Zendesk Groups API lets you programmatically manage the agent groups that power ticket routing and workflows in Zendesk Support. With it, you can create, list, retrieve, update, and delete groups, as well as fetch the set of groups a user can assign tickets to (assignable groups). Groups are used in ticket assignment, views, macros, and business rules like triggers and automations, so the API enables you to integrate group management into your provisioning and operations tooling.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/groups/groups/](https://developer.zendesk.com/api-reference/ticketing/groups/groups/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Groups

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/groups/groups/)
- [OpenAPI](openapi/groups-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Imports API

The Zendesk Imports API lets you programmatically load large volumes of records into Zendesk in a controlled, asynchronous wayideal for migrations, initial seeding, or ongoing syncs. You submit a file or batched payload, define which object type to import (for example, users/organizations/tickets in Support or leads/contacts/deals in Sell), and map fields. The import runs as a background job you can monitor via status endpoints, with progress, per-row validation, and detailed error reporting.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_import/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_import/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Imports

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_import/)
- [OpenAPI](openapi/imports-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Incremental API

The Zendesk Incremental API lets you export only the records that have changed since a specific point in time, making it easy to keep external systems in sync without repeatedly pulling full datasets. It supports core objects such as tickets, users, organizations, and ticket events, returning results in chronological order along with a checkpoint (an end_time or a cursor) you store and use on your next request to continue exactly where you left off.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/incremental_exports/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/incremental_exports/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Incremental

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/incremental_exports/)
- [OpenAPI](openapi/incremental-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Job Statuses

Zendesk Job Statuses is the mechanism and API resource that tracks long-running, asynchronous tasks kicked off in Zendesksuch as bulk ticket updates, user or organization imports, and other create/update many operations. Instead of waiting for a synchronous response, these endpoints return a job ID that you can poll to see whether the work is queued, in progress, or completed, along with progress counts, result details, and any errors.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/job_statuses/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/job_statuses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Jobs
- Statuses

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/job_statuses/)
- [OpenAPI](openapi/job-statuses-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Locales API

The Zendesk Locales API is a read-only service that lets you discover which languages and regional variants Zendesk supports and which are enabled on your account. It provides lists of all supported locales, the subsets available to end users and to agents, and the current users locale, along with metadata such as the locale code (for example, en-US), display name, and whether the language is right-to-left.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/locales/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/locales/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Locales

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/locales/)
- [OpenAPI](openapi/locales-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Macros API

The Zendesk Macros API lets you programmatically manage the reusable, predefined actions that agents apply to Support tickets. With it, you can list, create, update, delete, and reorder macros; fetch details and available action definitions to build editors; and determine which macros are available for a given ticket and user.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/macros/](https://developer.zendesk.com/api-reference/ticketing/business-rules/macros/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Macros

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/macros/)
- [OpenAPI](openapi/macros-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Oauth API

The Zendesk OAuth API implements the OAuth 2.0 standard to let apps securely access Zendesk data on a users or accounts behalf without sharing passwords. Developers register an OAuth client in a Zendesk account, redirect users to Zendesk for signin and consent, and exchange the returned authorization code for access (and optionally refresh) tokens.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/oauth/oauth_tokens/](https://developer.zendesk.com/api-reference/ticketing/oauth/oauth_tokens/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Authentication
- Authorization
- Oauth

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/oauth/oauth_tokens/)
- [OpenAPI](openapi/oauth-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Object Layouts API

The Zendesk Object Layouts API lets you programmatically control how record pages look and behave in Agent Workspace. It provides CRUD endpoints to define which fields and components appear for an object (such as tickets, users, organizations, and Sunshine custom objects), how theyre grouped and ordered into sections or panels, and any conditional visibility rules.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/introduction/](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Object Layouts

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/introduction/)
- [OpenAPI](openapi/object-layouts-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Organization Fields API

The Zendesk Organization Fields API lets you define and manage the custom fields that appear on organization records in Zendesk Support. You can list and inspect existing fields; create new ones with types like text, textarea, checkbox, date, integer, decimal, regexp-validated text, and dropdown (with custom options); update labels, descriptions, keys, active state, and position; reorder how fields appear; and delete fields you no longer need (system fields cant be removed).

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organization_fields/](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_fields/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Organization Fields

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_fields/)
- [OpenAPI](openapi/organization-fields-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Organization Memberships API

The Zendesk Organization Memberships API lets you programmatically manage the links between users and organizations in Zendesk. With it, you can create, list, find, and delete organization membership records; query memberships for a specific user or organization or across the account; set a users default organization; and perform bulk create/destroy operations to keep memberships in sync with external directories.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organization_memberships/](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_memberships/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Organization Memberships

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_memberships/)
- [OpenAPI](openapi/organization-memberships-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Organization Merges API

Zendesks Organization Merges API lets you consolidate two organizations into one clean record by merging a source organization into a target. During a merge, all users belonging to the source organization are moved to the target, and tickets associated with the source (as requester or via organization) are re-associated to the target, preserving ticket history and continuity.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Organization Merges

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- [OpenAPI](openapi/organization-merges-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Organization Subscriptions API

The Zendesk Organization Subscriptions API lets you programmatically manage which users follow an organization so they automatically receive notifications about that organizations ticket activity. Using it, you can create and delete subscriptions, list who is subscribed to a specific organization, list the organizations a user is subscribed to, and retrieve individual subscription records.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organization_subscriptions/](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_subscriptions/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Organization Subscriptions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organization_subscriptions/)
- [OpenAPI](openapi/organization-subscriptions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Organizations API

The Zendesk Organizations API is a RESTful interface for managing the companies or groups that your users belong to in Zendesk Support. It lets you create, read, update, and delete organizations; set attributes like domains, notes, tags, external_id, and custom fields; and configure behaviors such as shared tickets and comments. You can search and list organizations, use autocomplete, merge duplicates, and perform bulk operations via asynchronous jobs to import or update many records at once.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Organizations

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/organizations/organizations/)
- [OpenAPI](openapi/organizations-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/zendesk-support-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/zendesk-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zendesk Problems API

The Zendesk Problems API helps you manage problem tickets and their relationship to incident tickets, so you can track and resolve widespread issues affecting multiple customers. It provides endpoints to list and query problem tickets and to retrieve the incidents linked to a specific problem (for example, to understand scope and impact).

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Problems

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- [OpenAPI](openapi/problems-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Push Notification Devices API

The Zendesk Push Notification Devices API lets you register and manage the mobile devices that should receive push notifications for a given Zendesk user. With it, you can create device records using the apps push token (APNs for iOS, FCM/GCM for Android), list the devices linked to a user, update or disable a device entry, and delete registrations when a user signs out or a device is replaced.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/push_notification_devices/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/push_notification_devices/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Devices
- Push Notifications

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/push_notification_devices/)
- [OpenAPI](openapi/push-notification-devices-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Queues API

The Zendesk Queues API provides programmatic control over the queues that route work to agents across channels, letting you define and manage how tickets, messages, or calls are prioritized and assigned, and monitor how those queues are performing.

- **Human URL:** [https://developer.zendesk.com/api-reference/agent-availability/omnichannel_routing_queues/omnichannel_routing_queues/](https://developer.zendesk.com/api-reference/agent-availability/omnichannel_routing_queues/omnichannel_routing_queues/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Queues

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/agent-availability/omnichannel_routing_queues/omnichannel_routing_queues/)
- [OpenAPI](openapi/queues-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Recipient Addresses API

The Zendesk Recipient Addresses API lets you programmatically manage the email identities your Zendesk Support account can send from in ticket notifications. It allows you to list existing addresses, create new ones (often associated with specific brands), update properties like the display name, initiate or check verification status, set a default sender, and delete addresses.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/support_addresses/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/support_addresses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Addresses
- Recipients

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/support_addresses/)
- [OpenAPI](openapi/recipient-addresses-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Relationships API

The Zendesk Relationships API lets you model, create, and query links between data entities in Zendesk, spanning both standard resources (like users, organizations, and tickets) and Custom Objects. You define relationship types with explicit cardinality (one-to-one, one-to-many, or many-to-many), then create relationship records that connect specific instancesfor example, associating a customer with their devices, subscriptions, or locations, or tying tickets to assets or accounts.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/lookup_relationships/lookup_relationships/](https://developer.zendesk.com/api-reference/ticketing/lookup_relationships/lookup_relationships/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Relationships

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/lookup_relationships/lookup_relationships/)
- [OpenAPI](openapi/relationships-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Requests API

The Zendesk Requests API is the end-userfacing interface for support tickets, designed for customers to create, view, and update their own requests from web or mobile apps without agent credentials. It provides endpoints to submit a new request, list a users existing requests, get details for a specific request, add comments, include attachments (via upload tokens), and check request counts or status.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-requests/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-requests/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Requests

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-requests/)
- [OpenAPI](openapi/requests-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Resource Collections API

The Zendesk Resource Collections API provides a single, consistent way to list and retrieve Zendesk objectssuch as tickets, users, organizations, and knowledge contentwithout having to call productspecific endpoints. It exposes these objects as uniform collections that support filtering, sorting, field selection, and pagination, making it easier to fetch exactly the data your app or integration needs.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/resource_collections/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/resource_collections/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Collections
- Resources

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/resource_collections/)
- [OpenAPI](openapi/resource-collections-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Routing API

The Zendesk Routing API gives you programmatic control over how customer work is distributed to agents across channels. It lets you create and update work items (from tickets, messaging conversations, calls, or external tasks), enrich them with attributes such as skills, priority, and required capacity, and have Zendesks omnichannel router match them to available agents based on unified agent status and capacity limits.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Routing

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/)
- [OpenAPI](openapi/routing-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Satisfaction Ratings API

Zendesks Satisfaction Ratings API lets you programmatically work with customer satisfaction (CSAT) results tied to Support tickets. It provides endpoints to retrieve and page through ratings, fetch a single rating, and access details such as score (good/bad), optional comment, associated ticket, assignee, and timestampsso you can build custom reports, trigger automations, or sync CSAT data to other systems.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_ratings/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_ratings/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Satisfaction Ratings

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_ratings/)
- [OpenAPI](openapi/satisfaction-ratings-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Satisfaction Reasons API

The Zendesk Satisfaction Reasons API lets you programmatically manage the predefined list of reasons customers can choose when they leave a bad satisfaction rating on a ticket. With it, admins can list, create, update, reorder, activate/deactivate, and delete reasons that appear in the followup survey, ensuring the choices align with current operations or policies.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_reasons/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_reasons/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Satisfaction Reasons

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/satisfaction_reasons/)
- [OpenAPI](openapi/satisfaction-reasons-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Search API

The Zendesk Search API lets you programmatically find records across your Zendesk Support accountprimarily tickets, users, and organizationsusing a flexible query language that mixes free text with field-based filters (for example, type:ticket, status, tags, assignee, requester, or date ranges).

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/search/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/search/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Search

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/search/)
- [OpenAPI](openapi/search-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Sessions API

The Zendesk Sessions API lets you audit and control users active sign-in sessions in your Zendesk account. It provides endpoints to list current sessions (for the authenticated user or a specified user) and returns metadata such as device/user agent, IP, creation time, and last activity. You can revoke an individual session or all sessions for a user to force logouts across Zendesk web and mobile experiencesuseful for security incidents, offboarding, and SSO changes.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/sessions/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/sessions/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Sessions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/sessions/)
- [OpenAPI](openapi/sessions-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Sharing Agreements API

The Zendesk Sharing Agreements API lets you programmatically set up and manage ticketsharing relationships between separate Zendesk accounts so teams can collaborate on the same customer issues across instances. With it, you can create, list, update, and delete sharing agreements; send and respond to invitations; define rules and trust settings that control which tickets can be shared and what data is synchronized; and monitor or revoke agreements as needs change.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/sharing_agreements/](https://developer.zendesk.com/api-reference/ticketing/tickets/sharing_agreements/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Sharing Agreements

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/sharing_agreements/)
- [OpenAPI](openapi/sharing-agreements-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Skips API

The Zendesk Skips API provides programmatic access to events where an agent doesnt accept or actively skips a routed work item (such as a ticket or conversation) in omnichannel routing. It records who skipped, what was skipped, when it happened, and (when available) the reason, so you can analyze agent behavior, finetune routing rules and capacity, and troubleshoot assignment flows.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_skips/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_skips/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Skips

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_skips/)
- [OpenAPI](openapi/skips-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk SLAs API

The Zendesk SLAs API lets you programmatically manage and track service level agreement policies in Zendesk Support. It enables you to list, create, update, delete, and reorder SLA policies that set time targetsper priority and schedulefor metrics like first reply time, next reply time, periodic update, requester wait time, agent work time, and resolution time.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/sla_policies/](https://developer.zendesk.com/api-reference/ticketing/business-rules/sla_policies/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Service Level Agreements
- SLAs

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/sla_policies/)
- [OpenAPI](openapi/slas-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Suspended Tickets API

The Zendesk Suspended Tickets API lets you programmatically find and manage inbound emails that Zendesk quarantines as suspended before they become tickets. You can list and inspect these messagesincluding subject, body, sender, recipients, and the machine-readable reason they were suspended (such as spam, auto-reply, bounces, or mail loops)and then either recover them to create normal tickets or permanently delete them, individually or in bulk.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/suspended_tickets/](https://developer.zendesk.com/api-reference/ticketing/tickets/suspended_tickets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Suspended Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/suspended_tickets/)
- [OpenAPI](openapi/suspended-tickets-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Tags API

The Zendesk Tags API (part of the Support API) lets you programmatically manage the freeform tags used to categorize records in Zendesk. It provides REST endpoints to list all tags in an account (including occurrence counts), retrieve the tags on a specific ticket, user, or organization, and add, remove, or replace those tags. It also supports tag name autocomplete to help maintain consistency.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/tags/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/tags/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/tags/)
- [OpenAPI](openapi/tags-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Target Failures API

The Zendesk Target Failures API helps you monitor and troubleshoot failed delivery attempts to legacy targets (such as HTTP, URL, or email targets) that triggers and automations use to send outbound notifications. It lets you list and inspect recent failures for a target, including details like when they occurred, how many times delivery was attempted, the error or HTTP status returned by the destination, and other diagnostic information.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/targets/targets/](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Target Failures

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- [OpenAPI](openapi/target-failures-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Targets API

The Zendesk Targets API lets you programmatically manage targets, which are external destinations that Zendesk Support triggers and automations can notify when conditions are met. Using the API, you can create, list, update, activate/deactivate, and delete targets, configure details such as URLs, HTTP methods, authentication, and content types, and review delivery failures to troubleshoot outbound notifications.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/targets/targets/](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Targets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/targets/targets/)
- [OpenAPI](openapi/targets-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Audits API

The Zendesk Ticket Audits API exposes the complete, immutable change history of a Support ticket, letting you retrieve every audit generated whenever a ticket is created or updated. Each audit contains timestamped events that record who made a change and how it happened (agent, end user, trigger, automation, or API), along with metadata such as author, channel, and system details.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_audits/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_audits/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Audits
- Ticket Audits

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_audits/)
- [OpenAPI](openapi/ticket-audits-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Content Pins API

The Zendesk Ticket Content Pins API lets you programmatically manage the pinned references that keep important information visible on a support ticket. With it, you can create, list, reorder, and remove pins that point to helpful resources (such as Help Center articles or other relevant content) or key pieces of ticket context, so agents and collaborators always see the most important guidance first.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Pins
- Ticket Content

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- [OpenAPI](openapi/ticket-content-pins-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Fields API

The Zendesk Ticket Fields API lets you programmatically manage the structured fields that appear on Zendesk Support tickets.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_fields/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_fields/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Ticket Fields

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_fields/)
- [OpenAPI](openapi/ticket-fields-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Form Statuses API

The Zendesk Ticket Form Statuses API lets you control which ticket statuses (including custom ticket statuses) are available on each ticket form, so you can tailor status options to different request types or brands. With it, admins can retrieve the current status configuration for a form and update which statuses are enabled or hidden from agents and end users, helping simplify workflows and reduce confusion.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_form_statuses/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_form_statuses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Statuses
- Ticket Forms

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_form_statuses/)
- [OpenAPI](openapi/ticket-form-statuses-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Forms API

The Zendesk Ticket Forms API lets you programmatically create, read, update, delete, and reorder the ticket forms that shape how tickets are submitted and displayed in Zendesk Support. Each form defines which ticket fields appear and in what order, enabling you to tailor the submission experience for different request types, workflows, or brands. You can control properties such as the forms name and display name, whether its visible to end users, its default status, and its position.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_forms/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_forms/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Forms
- Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_forms/)
- [OpenAPI](openapi/ticket-forms-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Ticket Metrics API

The Zendesk Ticket Metrics API lets you programmatically access the operational and SLA metrics that Zendesk calculates for each support ticket. It provides perticket summaries such as first reply time, full resolution time, requester and agent wait times, onhold time, number of replies and reopens, and key timestamps (for example, assigned and solved), often available in both calendar and business minutes.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_metrics/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_metrics/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Metrics
- Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_metrics/)
- [OpenAPI](openapi/ticket-metrics-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Tickets API

The Zendesk Tickets API is the primary REST interface for managing support tickets programmatically. It lets you create, read, update, and delete tickets; set core and custom fields (status, priority, type, assignee, requester, organization, tags); and add public or internal comments with file attachments.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/tickets/)
- [OpenAPI](openapi/tickets-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/zendesk-support-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/zendesk-ticket-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zendesk-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zendesk Trigger Categories API

The Zendesk Trigger Categories API lets you programmatically organize Zendesk Support triggers into logical groups, making large sets of business rules easier to manage at scale. It provides endpoints to list and retrieve categories, create, rename, reorder, and delete them, and to assign or move triggers between categories or fetch the triggers within a category.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/](https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Categories
- Triggers

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/)
- [OpenAPI](openapi/trigger-categories-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Triggers API

The Zendesk Triggers API lets you programmatically manage the ticket triggers that power automation in Zendesk Support. Triggers are eventbased business rules that run immediately after a ticket is created or updated; when their conditions match, they perform actions like assigning or routing tickets, adding/removing tags, setting fields or status, sending notifications, and invoking webhooks.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/](https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Triggers

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/triggers/)
- [OpenAPI](openapi/triggers-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Uploads API

The Zendesk Uploads API lets you upload files to Zendesk Support so they can be attached to tickets or embedded inline in ticket comments. When you POST a file, the API creates an upload and returns metadata plus a short-lived token. You then include one or more of these tokens when creating or updating a ticket to add the files as attachments. The API supports single-shot and chunked uploads (for large files), and provides endpoints to check an uploads details or delete it.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Uploads

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket-attachments/)
- [OpenAPI](openapi/uploads-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk User Fields API

The Zendesk User Fields API lets you programmatically define and manage the custom attributes you store on users in Zendesk Support. You can list, create, update, and delete user fields (such as text, number, date, checkbox, or dropdown), which become part of your user schema and appear on user profiles for agents.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/users/users/](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- User Fields

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- [OpenAPI](openapi/user-fields-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Users API

The Zendesk Users API is part of the Zendesk Support REST API and lets you programmatically manage the people in your accountend users, agents, and admins. It provides endpoints to list, search, create, update, and delete users; manage roles, tags, custom fields, organization and group memberships; handle user identities (such as email addresses and phone numbers) and verification; set avatars; suspend or reactivate accounts; and merge duplicate users.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/users/users/](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Users

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/users/users/)
- [OpenAPI](openapi/users-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/zendesk-support-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/zendesk-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/zendesk-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Zendesk Views API

The Zendesk Views API lets you programmatically manage and use ticket viewsthe saved sets of filtering, sorting, and column rules that define agent queues. With it, you can list and fetch views (personal or shared), create, update, delete, and reorder them, and execute a view to retrieve the current tickets that match its conditions along with counts.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/business-rules/views/](https://developer.zendesk.com/api-reference/ticketing/business-rules/views/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Views

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/business-rules/views/)
- [OpenAPI](openapi/views-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Workspaces API

The Zendesk Workspaces API lets you programmatically create, read, update, delete, and prioritize contextual workspaces that shape the Agent Workspace experience. With it, admins define the conditions under which a workspace applies (for example by brand, channel, group, ticket form, or other ticket attributes) and configure what agents see and use when handling a ticketsuch as the ticket layout and fields, which sidebar apps open or are shown, and available tools or macros.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/workspaces/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/workspaces/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Workspaces

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/workspaces/)
- [OpenAPI](openapi/workspaces-openapi-original.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Zendesk Help Center Articles API

The Zendesk Help Center Articles API lets you programmatically manage knowledge base articles in your Help Center. You can create, read, update, and delete articles, manage their translations, set user segment permissions for viewing access, and organize articles within sections. The API supports searching articles, managing article labels, and controlling article visibility for agents and end users.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/articles/](https://developer.zendesk.com/api-reference/help_center/help-center-api/articles/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Articles
- Help Center
- Knowledge Base

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/articles/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Sections API

The Zendesk Help Center Sections API lets you create, read, update, and delete sections within your Help Center categories. Sections organize articles into logical groups and support multiple translations. You can specify user segment permissions to control viewing access and manage the ordering and placement of sections within categories.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/sections/](https://developer.zendesk.com/api-reference/help_center/help-center-api/sections/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Knowledge Base
- Sections

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/sections/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Categories API

The Zendesk Help Center Categories API lets you programmatically manage the top-level organizational structure of your knowledge base. You can create, read, update, and delete categories, specify names and locales, and optionally define multiple translations for each category to support multilingual Help Centers.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/categories/](https://developer.zendesk.com/api-reference/help_center/help-center-api/categories/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Categories
- Help Center
- Knowledge Base

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/categories/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Translations API

The Zendesk Help Center Translations API lets you manage multilingual content for articles, sections, and categories. You can create, read, update, and delete translations for Help Center content, list available locales, and check which translations are missing, enabling automated localization workflows and integration with external translation management systems.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/translations/](https://developer.zendesk.com/api-reference/help_center/help-center-api/translations/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Localization
- Translations

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/translations/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Article Attachments API

The Zendesk Help Center Article Attachments API lets you manage file attachments associated with Help Center articles. You can upload new attachments, list existing ones for an article, and delete attachments that are no longer needed. The API supports multipart form data uploads for images, documents, and other file types used in knowledge base content.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/article_attachments/](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_attachments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Articles
- Attachments
- Help Center

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_attachments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Article Comments API

The Zendesk Help Center Article Comments API lets you manage comments on knowledge base articles. Users can provide feedback by adding comments to articles, and the API provides endpoints to list, create, update, and delete comments. The user must have a Zendesk account and their requests must be authenticated to add comments.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/article_comments/](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_comments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Articles
- Comments
- Help Center

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_comments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Article Labels API

The Zendesk Help Center Article Labels API lets you manage the labels applied to knowledge base articles. Labels help categorize and organize articles for easier discovery. You can list labels on an article, add new labels, and remove existing ones, enabling automated content tagging and organization of your knowledge base.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/article_labels/](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_labels/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Articles
- Help Center
- Labels

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/article_labels/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Topics API

The Zendesk Help Center Topics API lets you manage community discussion topics in your Help Center. A topic represents a collection of community posts on a subject. You can create, read, update, and delete topics, set user segment permissions to control access, and organize community content for your users.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/topics/](https://developer.zendesk.com/api-reference/help_center/help-center-api/topics/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Community
- Help Center
- Topics

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/topics/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Posts API

The Zendesk Help Center Posts API lets you manage community posts within Help Center topics. You can list all posts, all posts in a given topic, or all posts by a specific user. The API provides endpoints to create, read, update, and delete community posts, enabling programmatic management of community discussions.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/posts/](https://developer.zendesk.com/api-reference/help_center/help-center-api/posts/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Community
- Help Center
- Posts

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/posts/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Post Comments API

The Zendesk Help Center Post Comments API lets you manage comments on community posts. You can list comments on a post, add new comments, update existing comments, and delete comments. This enables programmatic moderation and management of community discussions within Help Center.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/post_comments/](https://developer.zendesk.com/api-reference/help_center/help-center-api/post_comments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Comments
- Community
- Help Center

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/post_comments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Votes API

The Zendesk Help Center Votes API lets you access vote data for knowledge base and community content. You can list all votes cast by a given user, or all votes cast for a given article, article comment, post, or post comment. This enables reporting on content quality and user engagement with your Help Center.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/votes/](https://developer.zendesk.com/api-reference/help_center/help-center-api/votes/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Votes

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/votes/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Content Subscriptions API

The Zendesk Help Center Content Subscriptions API lets users subscribe to sections, articles, community posts, and community topics to receive notifications when content is added or updated. Users are notified when articles are added to sections, comments are added to articles or posts, or posts are added to topics.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/content_subscriptions/](https://developer.zendesk.com/api-reference/help_center/help-center-api/content_subscriptions/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Subscriptions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/content_subscriptions/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center User Segments API

The Zendesk Help Center User Segments API lets you manage user segments that control access to Help Center content. User segments define groups of users who can view specific articles, sections, or topics. You can create, read, update, and delete segments, and apply them to content to restrict or grant viewing access based on user attributes.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/user_segments/](https://developer.zendesk.com/api-reference/help_center/help-center-api/user_segments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Permissions
- User Segments

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/user_segments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Permission Groups API

The Zendesk Help Center Permission Groups API lets you manage which agents can create, update, archive, and publish articles. A management permission group consists of a set of privileges, each mapped to a user segment. This enables fine-grained control over who can manage knowledge base content.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/permission_groups/](https://developer.zendesk.com/api-reference/help_center/help-center-api/permission_groups/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Management
- Permissions

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/permission_groups/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Help Center Search API

The Zendesk Help Center Search API provides three different search endpoints for finding content in your knowledge base. The Search Articles and Search Posts endpoints enable you to search for articles and posts respectively, while the Unified Search endpoint allows you to search across articles, posts, and external content in a single query.

- **Human URL:** [https://developer.zendesk.com/api-reference/help_center/help-center-api/search/](https://developer.zendesk.com/api-reference/help_center/help-center-api/search/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Help Center
- Search

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/help_center/help-center-api/search/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk API

The Zendesk Talk API is the reference API for managing Zendesk voice capabilities. It provides endpoints for managing phone numbers, digital lines, greetings, greeting categories, IVRs, IVR routes and menus, call recordings, agent availabilities, voice settings, call stats, current queue activity, and incremental call exports. It is part of the Zendesk v2 API and uses the same authentication and pagination conventions.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/introduction/](https://developer.zendesk.com/api-reference/voice/talk-api/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Phone
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/introduction/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Phone Numbers API

The Zendesk Talk Phone Numbers API lets you manage the phone numbers in your Zendesk voice account. You can list existing phone numbers, search for available numbers to purchase, and manage phone number configurations for your Talk instance.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/phone_numbers/](https://developer.zendesk.com/api-reference/voice/talk-api/phone_numbers/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Phone Numbers
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/phone_numbers/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Greetings API

The Zendesk Talk Greetings API lets you manage the greetings used in your Zendesk voice account. Zendesk provides default greetings, but you can replace them with custom greetings by uploading mp3 or wav files. Greetings are assigned to greeting categories and used in IVR menus and call routing flows.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/greetings/](https://developer.zendesk.com/api-reference/voice/talk-api/greetings/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Greetings
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/greetings/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk IVRs API

The Zendesk Talk IVRs API lets you manage Interactive Voice Response systems that use keypad tones to route customers to the right agent or department, provide recorded responses for frequently asked questions, and deflect calls. IVR is available on Talk Professional and Enterprise plans. The API covers IVRs, IVR menus, and IVR routes.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/ivrs/](https://developer.zendesk.com/api-reference/voice/talk-api/ivrs/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- IVR
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/ivrs/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Recordings API

The Zendesk Talk Recordings API lets you manage call recordings stored by Talk. Recordings are exposed in the corresponding ticket in a voice comment. The API provides endpoints to retrieve and delete recordings associated with calls, supporting compliance and data retention requirements.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/recordings/](https://developer.zendesk.com/api-reference/voice/talk-api/recordings/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Recordings
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/recordings/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Stats API

The Zendesk Talk Stats API provides access to call statistics and current queue activity for your voice account. You can retrieve agent overview metrics including average talk time, available time, and accepted transfers. The current queue activity endpoint provides real-time visibility into call volume, wait times, and agent activity.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/stats/](https://developer.zendesk.com/api-reference/voice/talk-api/stats/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Statistics
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/stats/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Availabilities API

The Zendesk Talk Availabilities API lets you manage and query agent availability for voice calls. It provides information about agent state, call status, and connection method, enabling real-time monitoring of which agents are available to take calls and their current activity status.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/availabilities/](https://developer.zendesk.com/api-reference/voice/talk-api/availabilities/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Availabilities
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/availabilities/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Lines API

The Zendesk Talk Lines API lets you list the available lines, including both phone numbers and digital lines, in your Zendesk voice account. This provides a unified view of all voice communication channels configured for your Talk instance.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/lines/](https://developer.zendesk.com/api-reference/voice/talk-api/lines/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Lines
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/lines/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Digital Lines API

The Zendesk Talk Digital Lines API lets you manage the digital lines in your Zendesk voice account. Digital lines enable browser-based calling without traditional phone numbers, providing an additional channel for voice communications within your Talk setup.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/digital_lines/](https://developer.zendesk.com/api-reference/voice/talk-api/digital_lines/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Digital Lines
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/digital_lines/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Voice Settings API

The Zendesk Talk Voice Settings API lets you view and manage the account settings of your Zendesk voice account. It provides endpoints to retrieve and update configuration options that control how your Talk instance operates.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-api/voice_settings/](https://developer.zendesk.com/api-reference/voice/talk-api/voice_settings/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Settings
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-api/voice_settings/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Talk Partner Edition API

The Zendesk Talk Partner Edition API includes a Standard Call Object with endpoints to save, read, and update call-related data in Zendesk. It enables telephony partners to integrate their calling solutions with Zendesk by providing a standardized way to create and manage call records associated with support tickets.

- **Human URL:** [https://developer.zendesk.com/api-reference/voice/talk-partner-edition-api/introduction/](https://developer.zendesk.com/api-reference/voice/talk-partner-edition-api/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Partner Edition
- Talk
- Voice

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/voice/talk-partner-edition-api/introduction/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Accounts API

The Zendesk Chat Accounts API lets you get or set account information for your Zendesk Chat instance. If you created your Zendesk Chat account in Zendesk Support, access to the Chat Accounts and Agents APIs is restricted to GET requests. You can still use the other Chat APIs normally.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/accounts/](https://developer.zendesk.com/api-reference/live-chat/chat-api/accounts/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Accounts
- Chat

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/accounts/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Agents API

The Zendesk Chat Agents API lets you get or set agent information for your Zendesk Chat instance. If you created your Zendesk Chat account in Zendesk Support, access to the Agents API is restricted to GET requests, but you can still use other Chat APIs normally.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/agents/](https://developer.zendesk.com/api-reference/live-chat/chat-api/agents/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Agents
- Chat

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/agents/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Visitors API

The Zendesk Chat Visitors API lets you get or set visitor information for your Zendesk Chat instance. Visitors represent end users who initiate chat sessions through the Zendesk Chat widget on your website or application.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/visitors/](https://developer.zendesk.com/api-reference/live-chat/chat-api/visitors/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Visitors

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/visitors/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Chats API

The Zendesk Chat Chats API provides access to individual chat records with information including agent IDs, agent names, department information, chat history, conversions, and goal attributions. You can list and search chat transcripts for reporting, compliance, and quality assurance purposes.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Conversations

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/chats/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Departments API

The Zendesk Chat Departments API lets you get or set department information for your Chat instance. Departments enable you to route chats to specific groups of agents, configure operating hours, and organize your chat support by team or function.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/departments/](https://developer.zendesk.com/api-reference/live-chat/chat-api/departments/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Departments

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/departments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Shortcuts API

The Zendesk Chat Shortcuts API lets you manage canned responses that agents can use during live chat conversations. You can list all shortcuts for the account, create new ones, update existing shortcuts, and delete them, with support for scoping by departments and agents.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/shortcuts/](https://developer.zendesk.com/api-reference/live-chat/chat-api/shortcuts/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Shortcuts

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/shortcuts/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Triggers API

The Zendesk Chat Triggers API lets you manage proactive chat triggers that automatically engage visitors based on specified conditions. You can list triggers, add new triggers, update, and delete them. Chat triggers can be set to run when a visitor loads the chat widget or based on other visitor activity.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/triggers/](https://developer.zendesk.com/api-reference/live-chat/chat-api/triggers/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Triggers

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/triggers/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Bans API

The Zendesk Chat Bans API lets you manage banned visitors in your Chat account. You can list banned visitors with cursor-based pagination, create new bans, and remove existing bans to control which visitors can access your live chat.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/bans/](https://developer.zendesk.com/api-reference/live-chat/chat-api/bans/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Bans
- Chat

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/bans/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Roles API

The Zendesk Chat Roles API lets you manage agent roles and permissions within your Chat account. You can retrieve role definitions and manage role assignments to control what actions different agents can perform in the chat interface.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/roles/](https://developer.zendesk.com/api-reference/live-chat/chat-api/roles/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Roles

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/roles/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Skills API

The Zendesk Chat Skills API lets you manage skills used for routing chats to qualified agents. You can get or set skill information, enabling skills-based routing where chats are directed to agents with specific expertise or language capabilities.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/skills/](https://developer.zendesk.com/api-reference/live-chat/chat-api/skills/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Skills

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/skills/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Goals API

The Zendesk Chat Goals API lets you manage conversion goals for your Chat account. Goals track specific visitor actions such as page visits or purchases that occur during or after a chat session, enabling you to measure the impact of chat on business outcomes.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/goals/](https://developer.zendesk.com/api-reference/live-chat/chat-api/goals/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Goals

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/goals/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Routing Settings API

The Zendesk Chat Routing Settings API lets you get or modify chat routing settings for your account. It controls how incoming chats are distributed to available agents based on configured rules and policies.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-api/routing_settings/](https://developer.zendesk.com/api-reference/live-chat/chat-api/routing_settings/)
- **Base URL:** `https://www.zopim.com`

#### Tags

- Chat
- Routing

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-api/routing_settings/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Real-Time Chat API

The Zendesk Real-Time Chat API provides streaming access to real-time chat metrics and activity data. It enables building live dashboards and monitoring tools that display current chat volume, agent activity, and visitor information as events occur.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/real-time-chat-api/introduction/](https://developer.zendesk.com/api-reference/live-chat/real-time-chat-api/introduction/)
- **Base URL:** `https://rtm.zopim.com`

#### Tags

- Chat
- Real-Time
- Streaming

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/real-time-chat-api/introduction/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Chat Conversations API

The Zendesk Chat Conversations API lets your application act as a Zendesk Chat agent and interact with customers. It is a GraphQL API that supports WebSocket connections for real-time message exchange. Note that this API is in maintenance mode and is not receiving new features.

- **Human URL:** [https://developer.zendesk.com/api-reference/live-chat/chat-conversations-api/conversations-api/](https://developer.zendesk.com/api-reference/live-chat/chat-conversations-api/conversations-api/)
- **Base URL:** `https://chat-api.zopim.com`

#### Tags

- Chat
- Conversations
- GraphQL

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/live-chat/chat-conversations-api/conversations-api/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Webhooks API

The Zendesk Webhooks API lets you create, manage, and monitor webhooks that send HTTP requests to specified URLs in response to events in Zendesk. It is the modern replacement for legacy targets, supporting event types for tickets, users, organizations, and messaging. You can create, list, update, test, and delete webhooks, and inspect invocation logs for troubleshooting.

- **Human URL:** [https://developer.zendesk.com/api-reference/webhooks/webhooks-api/webhooks/](https://developer.zendesk.com/api-reference/webhooks/webhooks-api/webhooks/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Webhooks

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/webhooks/webhooks-api/webhooks/)
- [AsyncAPI](asyncapi/zendesk-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Contacts API

The Zendesk Sell Contacts API provides a simple interface to manage your contacts. A contact represents an individual or an organization. Each contact has customer_status and prospect_status fields describing the relationship to your business. You can create, read, update, and delete contacts.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/contacts/](https://developer.zendesk.com/api-reference/sales-crm/resources/contacts/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- Contacts
- CRM
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/contacts/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Leads API

The Zendesk Sell Leads API provides a simple interface to manage leads. A lead represents an individual or organization that expresses interest in your goods or services. You can create, read, update, and delete leads, and retrieve individual leads as well as lists of all leads.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/leads/](https://developer.zendesk.com/api-reference/sales-crm/resources/leads/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Leads
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/leads/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Deals API

The Zendesk Sell Deals API provides a simple interface to manage deals. You can create, delete, and update deals, retrieve individual deals or lists of all deals. Every deal can have multiple associated contacts with different roles, and deals progress through pipeline stages.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/deals/](https://developer.zendesk.com/api-reference/sales-crm/resources/deals/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Deals
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/deals/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Pipelines API

The Zendesk Sell Pipelines API provides a read-only interface to your sales pipeline definitions. Sales pipelines consist of a sequence of stages that deals progress through as they move toward closing.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/pipelines/](https://developer.zendesk.com/api-reference/sales-crm/resources/pipelines/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Pipelines
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/pipelines/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Stages API

The Zendesk Sell Stages API provides read-only access to details of your sales pipeline stages. Stages are key components of a sales pipeline, and each stage can have any number of deals associated with it.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/stages/](https://developer.zendesk.com/api-reference/sales-crm/resources/stages/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Sell
- Stages

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/stages/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Tasks API

The Zendesk Sell Tasks API provides a simple interface to manage tasks. A task can be either floating (associated only with a user) or related (associated with a lead, contact, or deal). You can create, read, update, and delete tasks.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/tasks/](https://developer.zendesk.com/api-reference/sales-crm/resources/tasks/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Sell
- Tasks

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/tasks/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Notes API

The Zendesk Sell Notes API provides a simple interface to manage notes. You can create, read, update, and delete notes associated with leads, contacts, and deals in your CRM.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/notes/](https://developer.zendesk.com/api-reference/sales-crm/resources/notes/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Notes
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/notes/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Calls API

The Zendesk Sell Calls API lets you create, read, and delete call records in your CRM. Calls can be associated with leads, contacts, and deals to maintain a complete activity history for your sales team.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/calls/](https://developer.zendesk.com/api-reference/sales-crm/resources/calls/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- Calls
- CRM
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/calls/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Text Messages API

The Zendesk Sell Text Messages API provides read-only access to text messages sent and received within Zendesk Sell. You can retrieve individual messages and list all text messages for reporting and integration purposes.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/text-messages/](https://developer.zendesk.com/api-reference/sales-crm/resources/text-messages/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Sell
- Text Messages

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/text-messages/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Products API

The Zendesk Sell Products API lets you manage your product catalog. You can create, read, update, and delete products. To add products to a deal, create an Order and then populate it with Line Items referencing products from the catalog.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/products/](https://developer.zendesk.com/api-reference/sales-crm/resources/products/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Products
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/products/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Orders API

The Zendesk Sell Orders API provides a simple interface to manage orders. An order is a list of line items associated with a deal. You can create, read, update, and delete orders to track products and pricing within your deals.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/orders/](https://developer.zendesk.com/api-reference/sales-crm/resources/orders/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Orders
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/orders/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Line Items API

The Zendesk Sell Line Items API lets you manage individual line items within orders. Line items correspond to products in your catalog and include quantity, pricing, and currency information for each product associated with a deal.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/line-items/](https://developer.zendesk.com/api-reference/sales-crm/resources/line-items/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Line Items
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/line-items/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Collaborations API

The Zendesk Sell Collaborations API provides a simple interface to manage collaborations. You can create, read, and delete collaborations to enable team members to work together on leads, contacts, and deals.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/collaborations/](https://developer.zendesk.com/api-reference/sales-crm/resources/collaborations/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- Collaborations
- CRM
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/collaborations/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Sequences API

The Zendesk Sell Sequences API provides a read-only interface to sequences. A sequence is a set of steps with timeliness of their execution, where each step can be either an automated email or a task, enabling automated sales outreach workflows.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/sequences/](https://developer.zendesk.com/api-reference/sales-crm/resources/sequences/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Sell
- Sequences

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/sequences/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Lead Sources API

The Zendesk Sell Lead Sources API provides a simple interface to manage lead sources. You can create, read, update, and delete sources to track where your leads originate from.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/lead-sources/](https://developer.zendesk.com/api-reference/sales-crm/resources/lead-sources/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Lead Sources
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/lead-sources/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Deal Sources API

The Zendesk Sell Deal Sources API provides a simple interface to manage deal sources. You can create, read, update, and delete sources to track where your deals originate from.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/deal-sources/](https://developer.zendesk.com/api-reference/sales-crm/resources/deal-sources/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Deal Sources
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/deal-sources/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Lead Conversions API

The Zendesk Sell Lead Conversions API provides a simple interface to manage lead conversions. You can create or read lead conversions that transform leads into contacts and optionally create associated deals.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/lead-conversions/](https://developer.zendesk.com/api-reference/sales-crm/resources/lead-conversions/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Lead Conversions
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/lead-conversions/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Tags API

The Zendesk Sell Tags API provides a simple interface to manage tags. You can create, read, update, and delete tags used to categorize and organize leads, contacts, and deals in your CRM.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/tags/](https://developer.zendesk.com/api-reference/sales-crm/resources/tags/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/tags/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sell Custom Fields API

The Zendesk Sell Custom Fields API lets you manage custom fields for leads, contacts, and deals. You can assign any number of custom fields as key-value pairs. Custom fields must first be created in the user interface before they can be managed via the API.

- **Human URL:** [https://developer.zendesk.com/api-reference/sales-crm/resources/custom-fields/](https://developer.zendesk.com/api-reference/sales-crm/resources/custom-fields/)
- **Base URL:** `https://api.getbase.com`

#### Tags

- CRM
- Custom Fields
- Sell

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/sales-crm/resources/custom-fields/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Sunshine Conversations API

The Zendesk Sunshine Conversations API is a messaging platform that lets you unify messages from every channel into a single conversation and build interactive experiences. You can programmatically manage users and conversations, send messages, use webhooks for real-time events, send targeted outbound messages on WhatsApp or SMS, and customize switchboard for bot orchestration flows.

- **Human URL:** [https://developer.zendesk.com/api-reference/conversations/](https://developer.zendesk.com/api-reference/conversations/)
- **Base URL:** `https://api.smooch.io`

#### Tags

- Conversations
- Messaging
- Sunshine

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/conversations/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Omnichannel API

The Zendesk Omnichannel API provides access to agent availability and status information across Zendesk channels. It includes unified and custom agent statuses, per-channel agent statuses, assigned work items per channel, and agent max capacity per channel. This enables real-time monitoring and management of agent availability for omnichannel routing.

- **Human URL:** [https://developer.zendesk.com/api-reference/agent-availability/introduction/](https://developer.zendesk.com/api-reference/agent-availability/introduction/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Agent Availability
- Omnichannel
- Routing

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/agent-availability/introduction/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Unified Agent Statuses API

The Zendesk Unified Agent Statuses API lets you manage and query unified agent statuses that span across all channels in omnichannel routing. It provides a single view of each agent's availability state, enabling consistent status management and monitoring across Support, Messaging, and Talk channels.

- **Human URL:** [https://developer.zendesk.com/api-reference/agent-availability/unified-agent-status-api/unified_agent_statuses/](https://developer.zendesk.com/api-reference/agent-availability/unified-agent-status-api/unified_agent_statuses/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Agent Status
- Omnichannel

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/agent-availability/unified-agent-status-api/unified_agent_statuses/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Omnichannel Engagements API

The Zendesk Omnichannel Engagements API provides access to engagement data for agents across all channels. It enables tracking and reporting on how agents interact with work items, including assignment history, response metrics, and engagement patterns across Support, Messaging, and Talk.

- **Human URL:** [https://developer.zendesk.com/api-reference/agent-availability/omnichannel-engagements/omnichannel_engagements/](https://developer.zendesk.com/api-reference/agent-availability/omnichannel-engagements/omnichannel_engagements/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Engagements
- Omnichannel

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/agent-availability/omnichannel-engagements/omnichannel_engagements/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Apps API

The Zendesk Apps API lets you manage apps installed on your Zendesk account. It lists all public apps on the Zendesk Marketplace, and for authenticated agents and admins, also lists private apps. You can install, update, and remove apps, and manage app configurations.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/apps/apps/](https://developer.zendesk.com/api-reference/ticketing/apps/apps/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Apps
- Marketplace

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/apps/apps/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Account Settings API

The Zendesk Account Settings API lets you view and manage the configuration settings for your Zendesk Support account, including settings for tickets, agents, security, branding, and other account-wide options that control how your Zendesk instance operates.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/account-configuration/account_settings/](https://developer.zendesk.com/api-reference/ticketing/account-configuration/account_settings/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Account Settings
- Configuration

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/account-configuration/account_settings/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Schedules API

The Zendesk Schedules API lets you manage business hour schedules that define when your support team is available. Schedules are used by SLA policies, triggers, automations, and other business rules to calculate response and resolution times based on business hours rather than calendar hours.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/schedules/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/schedules/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Business Hours
- Schedules

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/schedules/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk User Identities API

The Zendesk User Identities API lets you manage the email addresses, phone numbers, X (Twitter) handles, and other identities associated with a user. You can list, create, update, verify, and delete identities, set a primary identity, and manage how users are identified across channels.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/users/user_identities/](https://developer.zendesk.com/api-reference/ticketing/users/user_identities/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Identities
- Users

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/users/user_identities/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Ticket Comments API

The Zendesk Ticket Comments API lets you manage comments on support tickets. Comments are the public and internal messages exchanged between agents, end users, and collaborators on a ticket. You can list comments, add new public or internal comments with attachments, and redact sensitive information from existing comments.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Comments
- Tickets

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/tickets/ticket_comments/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zendesk Skill-Based Routing API

The Zendesk Skill-Based Routing API lets you manage skills and skill-based routing rules that match tickets to agents with the right expertise. You can define skills such as language fluency or product knowledge, assign them to agents, and create routing rules that ensure tickets are directed to qualified agents.

- **Human URL:** [https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/](https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/)
- **Base URL:** `https://{subdomain}.zendesk.com`

#### Tags

- Routing
- Skills

#### Properties

- [Documentation](https://developer.zendesk.com/api-reference/ticketing/ticket-management/skill_based_routing/)
- [Postman Collection](collections/zendesk-support.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zendesk-support.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/zendesk)
- [Privacy Policy](https://www.zendesk.com/company/agreements-and-terms/privacy-notice/)
- [Status Page](https://status.zendesk.com/)
- [Terms of Service](https://www.zendesk.com/company/agreements-and-terms/zendesk-customer-agreement/)
- [Blog](https://www.zendesk.com/help-center-closed/?utm_source=helpcenter-closed&utm_medium=poweredbyzendesk&utm_campaign=text&utm_content=developerblog.zendesk.com)
- [Marketplace](https://www.zendesk.com/marketplace/)
- [Pricing](https://www.zendesk.com/pricing/featured/?variant=518&targetRedirect=true)
- [Sign Up](https://www.zendesk.com/register/)
- [Security](https://www.zendesk.com/trust-center/)
- [Blog](https://www.zendesk.com/blog/)
- [Training](https://training.zendesk.com/?_gl=1*bjm8lh*_gcl_au*NzkzMDYzNTc4LjE3NTQzMzc4ODI.*_ga*ODQ3OTgwMzk0LjE3NTQzMzc4NDA.*_ga_FBP7C61M6Z*czE3NTQzMzc4ODkkbzEkZzEkdDE3NTQzMzgwODckajQ0JGwwJGgw)
- [Partners](https://www.zendesk.com/partner/)
- [Documentation](https://www.zendesk.com/)
- [Support](https://support.zendesk.com/hc/en-us/community/topics)
- [Documentation](https://developer.zendesk.com/documentation/webhooks/)
- [Portal](https://developer.zendesk.com/documentation)
- [Documentation](https://developer.zendesk.com/api-reference/)
- [Login](https://www.zendesk.com/login/)
- [Changelog](https://developer.zendesk.com/api-reference/changelog/changelog/)
- [Rate Limits](https://developer.zendesk.com/api-reference/introduction/rate-limits/)
- [Authentication](https://developer.zendesk.com/api-reference/introduction/security-and-auth/)
- [Support](https://support.zendesk.com/hc/en-us)
- [Getting Started](https://developer.zendesk.com/documentation/api-basics/getting-started/zendesk-api-resources/)
- [Documentation](https://www.postman.com/zendesk-redback/zendesk-public-api/overview)
- [GitHub Organization](https://github.com/zendesk)
- [C L I](https://github.com/zendesk/zcli)
- [GitHub Repository](https://github.com/zendesk/sunshine-conversations-api-spec)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

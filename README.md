# Stracture amarire.dev:
```
public_html/
├── index.php
├── .htaccess
├── favicon.ico
├── manifest.json
├── assets/
│   ├── css/
│   │   ├── header.css
│   │   ├── home.css
│   │   ├── auth.css
│   │   └── footer.css
│   ├── js/
│   │   ├── header.js
│   │   ├── home.js
│   │   └── footer.js
│   ├── images/
│   │   ├── global/
│   │   │   ├── logo-light.webp
│   │   │   └── logo-dark.webp
│   │   ├── seo/
│   │   ├── projects/
│   │   └── demos/
│   ├── fonts/
│   │   ├── Montserrat-ThinItalic.woff2
│   │   └── Montserrat-ThinItalic.woff
│   └── media/
├── views/
│   ├── .htaccess
│   ├── layouts/
│   │   ├── head.php
│   │   ├── header.php
│   │   ├── footer.php
│   │   └── main.php
│   ├── pages/
│   │   ├── home.php
│   │   ├── about.php
│   │   ├── projects.php
│   │   ├── project_single.php
│   │   ├── contact.php
│   │   ├── subject.php
│   │   ├── dashboard/
│   │   |   ├── index.php
│   │   |   ├── files_manager.php
│   │   |   ├── invoices_list.php
│   │   |   ├── projects_list.php
│   │   |   ├── requests_new.php
│   │   |   ├── account_settings.php
│   │   |   └── welcome_intro.php
│   │   ├── payment/
│   │   |   ├── checkout.php
│   │   |   ├── process.php
│   │   |   ├── success.php
│   │   |   ├── manual_payment.php
│   │   |   ├── receipt_template.php
│   │   |   ├── receipt_pdf.php
│   │   |   └── verify_result.php
│   │   ├── services/
│   │   |   ├── index.php
│   │   |   ├── all.php
│   │   |   ├── single.php
│   │   |   ├── packages.php
│   │   |   └── request.php
│   │   ├── login.php
│   │   ├── register.php
│   │   ├── verify.php
│   │   ├── forgot_password.php
│   │   ├── reset_password.php
│   │   ├── admin/
│   │   │   └── upload_invoice.php
│   │   └── demos/
│   │       └── birthday/boys/ar.php
│   ├── components/
│   │   ├── navbar.php
│   │   ├── seo_schema.php
│   │   └── chatbot_widget.php
│   ├── emails/
│   │   ├── verification_code.php
│   │   ├── welcome.php
│   │   └── reset_password.php
│   ├── partials/
│   │   └── pagination.php
│   └── errors/
│       ├── 400.php
│       ├── 401.php
│       ├── 403.php
│       ├── 404.php
│       ├── 500.php
│       └── 503.php
└── _private/
    ├── .htaccess
    ├── .env
    ├── _app/
    │   ├── kernel.php
    │   ├── config/
    │   │   ├── app.php
    │   │   ├── database.php
    │   │   ├── currency.php
    │   │   ├── security.php
    │   │   ├── seo.php
    │   │   ├── ai.php
    │   │   └── payment.php
    │   ├── core/
    │   │   ├── Router.php
    │   │   ├── View.php
    │   │   ├── Config.php
    │   │   ├── Database.php
    │   │   ├── Request.php
    │   │   ├── Response.php
    │   │   ├── Validator.php
    │   │   ├── Security.php
    │   │   └── Session.php
    │   ├── controllers/
    │   │   ├── web/
    │   │   │   ├── HomeController.php
    │   │   │   ├── PageController.php
    │   │   │   ├── DemoController.php
    │   │   │   ├── AuthController.php
    │   │   │   ├── DashboardController.php
    │   │   │   ├── InvoiceController.php
    │   │   │   ├── PaymentController.php
    │   │   │   ├── ServiceController.php
    │   │   │   ├── FormController.php
    │   │   │   ├── ChatbotController.php
    │   │   │   ├── AdminController.php
    │   │   │   ├── ReceiptController.php
    │   │   │   ├── VerifyController.php
    │   │   │   ├── EventController.php
    │   │   │   └── ApiController.php
    │   │   └── api/
    │   │       ├── v1/
    │   │       │   ├── ServiceApiController.php
    │   │       │   ├── AuthApiController.php
    │   │       │   ├── UserApiController.php
    │   │       │   ├── ServicesSearchApiController.php
    │   │       │   ├── ServicesOrderApiController.php
    │   │       │   ├── ProjectApiController.php
    │   │       │   ├── ServiceRequestApiController.php
    │   │       │   ├── DashboardApiController.php
    │   │       │   ├── ChatbotApiController.php
    │   │       │   ├── NotificationApiController.php
    │   │       │   ├── ContactApiController.php
    │   │       │   └── PaymentApiController.php
    │   │       └── v2/
    │   ├── models/
    │   │   ├── User.php
    │   │   ├── Visitor.php
    │   │   ├── Project.php
    │   │   ├── Currency.php
    │   │   ├── Order.php
    │   │   ├── Contact.php
    │   │   ├── Payment.php
    │   │   ├── Category.php
    │   │   ├── Service.php
    │   │   ├── Package.php
    │   │   ├── Addon.php
    │   │   ├── ServiceRequest.php
    │   │   ├── VisitorAnalytics.php
    │   │   ├── VisitorEvent.php
    │   │   ├── ChatMessage.php
    │   │   └── api/
    │   │       └── ApiRateLimit.php
    │   ├── services/
    │   │   ├── shared/
    │   │   |   ├── AuthService.php
    │   │   |   ├── ServiceManager.php
    │   │   |   ├── AnalyticsService.php
    │   │   |   ├── MailService.php
    │   │   |   ├── ProjectService.php
    │   │   |   ├── ServiceManager.php
    │   │   |   ├── ContactService.php
    │   │   |   ├── PaymentService.php
    │   │   |   ├── ReceiptService.php
    │   │   |   ├── AiService.php
    │   │   |   └── ChatbotService.php
    │   │   └── api/
    │   │       ├── TokenService.php
    │   │       ├── ApiLogger.php
    │   │       ├── ThrottleService.php
    │   │       ├── RateLimitService.php
    │   │       └── ServiceApiManager.php
    │   ├── ai/
    │   │   ├── OpenAIClient.php
    │   │   ├── PromptTemplates.php
    │   │   └── ConversationManager.php
    │   ├── seo/
    │   │   ├── SeoManager.php
    │   │   ├── OpenGraph.php
    │   │   ├── RobotsGenerator.php
    │   │   ├── AiSeoOptimizer.php
    │   │   ├── Schema.php
    │   │   ├── SitemapGenerator.php
    │   │   └── en/
    │   │   |   ├── home.php
    │   │   |   ├── contact.php
    │   │   |   ├── services.php
    │   │   |   └── projects.php
    │   │   └── fr/
    │   │   |   ├── home.php
    │   │   |   ├── contact.php
    │   │   |   ├── services.php
    │   │   |   └── projects.php
    │   │   └── ar/
    │   │   |   ├── home.php
    │   │   |   ├── contact.php
    │   │   |   ├── services.php
    │   │   |   └── projects.php
    │   │   └── ber/
    │   │       ├── home.php
    │   │       ├── contact.php
    │   │       ├── services.php
    │   │       └── projects.php
    │   ├── middleware/
    │   │   ├── web/
    │   │   |   ├── Csrf.php
    │   │   |   ├── Auth.php
    │   │   |   ├── Headers.php
    │   │   |   ├── Audit.php
    │   │   |   ├── MiddlewareStack.php
    │   │   |   └── Intrusion.php
    │   │   └── api/
    │   │       ├── ApiAuth.php
    │   │       ├── JwtAuth.php
    │   │       └── Cors.php
    │   ├── helpers/
    │   │   ├── url.php
    │   │   ├── CurrencyUpdater.php
    │   │   ├── currency.php
    │   │   ├── seo.php
    │   │   ├── assets.php
    │   │   ├── security.php
    │   │   └── i18n.php
    │   ├── api/
    │   │   ├── ApiGateway.php
    │   │   ├── resources/
    │   │   │   ├── ServiceResource.php
    │   │   │   └── UserResource.php
    │   │   ├── validators/
    │   │   │   └── SearchValidator.php
    │   │   ├── responses/
    │   │   │   └── ApiResponse.php
    │   ├── routes/
    │   │   ├── web.php
    │   │   └── api.php
    │   ├── i18n/
    │   │   ├── en/
    │   │   │   ├── ui.php
    │   │   │   ├── system.php
    │   │   │   ├── invoices.php
    │   │   │   ├── emails.php
    │   │   │   └── home.php
    │   │   ├── ar/
    │   │   ├── fr/
    │   │   └── ber/
    │   ├── monitoring/
    │   │   ├── AuditLogger.php
    │   │   ├── SecurityLogger.php
    │   │   ├── SystemLogger.php
    │   │   ├── IntrusionDetector.php
    │   │   └── IntegrityGuard.php
    │   ├── events/
    │   │   ├── UserLoginEvent.php
    │   │   ├── UserLogoutEvent.php
    │   │   ├── FileChangeEvent.php
    │   │   ├── DataUpdateEvent.php
    │   │   ├── FailedLoginEvent.php
    │   │   ├── ApiRequestEvent.php
    │   │   └── PaymentEvent.php
    │   ├── observers/
    │   │   ├── AuthObserver.php
    │   │   ├── FileObserver.php
    │   │   ├── DatabaseObserver.php
    │   │   └── RequestObserver.php
    │   ├── forensics/
    │   │   ├── SnapshotManager.php
    │   │   ├── HashGenerator.php
    │   │   └── EvidenceVault.php
    │   └── console/
    │       ├── generate-sitemap.php
    │       ├── export-i18n.php
    │       └── verify-integrity.php
    ├── storage/
    │   ├── .htaccess
    │   ├── uploads/
    │   │   └── invoices/
    │   ├── app/
    │   │   └── generated_receipts/
    │   ├── receipts/
    │   ├── cache/
    │   ├── sessions/
    │   ├── audit/
    │   │   ├── auth.log
    │   │   ├── actions.log
    │   │   ├── api.log
    │   │   ├── payments.log
    │   │   ├── uploads.log
    │   │   └── system.log
    │   ├── security/
    │   │   ├── attacks.log
    │   │   ├── intrusion.log
    │   │   ├── firewall.log
    │   │   └── brute-force.log
    │   ├── forensics/
    │   │   ├── hashes/
    │   │   ├── snapshots/
    │   │   ├── receipts/
    │   │   └── evidence/
    │   └── immutable/
    │       └── master.log
    ├── database/
    │   ├── .htaccess
    │   ├── core_schema.sql
    │   ├── app_schema.sql
    │   ├── migrations/up-db.php
    │   └── seeds/
    ├── legacy/
    │   ├── .htaccess
    │   ├── old_api.php 
    │   ├── deprecated.php
    │   └── bridge.php
    ├── backups/
    │   ├── .htaccess
    │   ├── daily/
    │   ├── weekly/
    │   └── monthly/
    └── vendor/
        ├── dompdf/
        │   ├── dompdf/
        │   ├── html5lib/
        │   ├── php-svg-lib/
        │   └── php-font-lib/
        ├── PHPMailer/
        ├── I18N/
        └── .htaccess
```

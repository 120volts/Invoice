# Architecture

Financial Brain ├─ Invoice ├─ Clients ├─ Projects ├─ Purchases ├─
Dashboard └─ Taxes

Invoice emits events such as: - InvoiceCreated - InvoiceSent -
InvoiceViewed - InvoicePaid - InvoiceOverdue

Other modules consume these events through interfaces.

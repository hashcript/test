# GlobPay System Setup Requirements

## Company Information
- **Company Name**: GlobPay
- **Domain**: globpay.ai
- **Contact**: David

---

## 1. Logo Requirements
- **Format**: SVG
- **Dimensions**: Width: 150px, Height: 30px
- **Ratio**: 5:1
- **Background Compatibility**: Must work on both dark and light backgrounds
- **Status**: ⏳ Pending

---

## 2. Subdomain Configuration

| Service | Subdomain | Purpose | Status |
|---------|-----------|---------|--------|
| Dashboard | `dashboard.globpay.ai` | System access portal | ⏳ Pending |
| API | `api.globpay.ai` | S2S protocol customization | ✅ Allocated |
| Payment Page | `pay.globpay.ai` | Payment page URL | ⏳ Pending |
| Documentation | `docs.globpay.ai` | Technical documentation | ⏳ Pending |
| Customer Invoices | `invoice.globpay.ai` | Invoice system (if needed) | ⏳ Pending |

**Note**: `sandbox.globpay.ai` and `api.globpay.ai` are already allocated.

---

## 3. DNS CNAME Configuration

| Service | Your Subdomain | CNAME Target | Status |
|---------|----------------|--------------|--------|
| Dashboard | `dashboard.globpay.ai` | `admin.rafinita.com` | ⏳ Pending |
| API | `api.globpay.ai` | `api.rafinita.com` | ⏳ Pending |
| Payment Page | `pay.globpay.ai` | `checkout.rafinita.com` | ⏳ Pending |
| Documentation | `docs.globpay.ai` | `docs.rafinita.com` | ⏳ Pending |
| Customer Invoice | `invoice.globpay.ai` | `invoice.rafinita.com` | ⏳ Pending |

---

## 4. SSL Certificate Requirements

### Certificate Specifications
- **Type**: Wildcard certificate (preferred) or individual certificates
- **Domain Coverage**: *.globpay.ai
- **Provider**: Certified providers (GoDaddy, NameCheap, etc.)
- **Alternative**: Rafinita can provide (cost: $90/month)

### Required Files
| File Type | Format | Description | Status |
|-----------|--------|-------------|--------|
| SSL Certificate | `.crt`, `.cert` | Main certificate file | ⏳ Pending |
| Private Key | `.key` | Corresponding private key | ⏳ Pending |
| CA Bundle | `.crt-bundle` | Certificate authority bundle | ⏳ Pending |

### Delivery Format
- **Archive**: All files should be sent as a single archive
- **File Formats**: .key, .crt, .crt-bundle, *.cert

---

## 5. Email Configuration
- **Notification Email**: `noreply@globpay.ai`
- **Purpose**: System notifications to dashboard users
- **Status**: ⏳ Pending

---

## 6. Login Page Branding Requirements

### Favicon Specifications
| Format | Size | Background | Status |
|--------|------|------------|--------|
| SVG/PNG/ICO | 48x48, 96x96, etc. | Transparent | ⏳ Pending |
| SVG/PNG/ICO | 48x48, 96x96, etc. | Solid color | ⏳ Pending |

### Page Customization
| Element | Requirement | Example | Status |
|---------|-------------|---------|--------|
| Background Color | Hex code | #FFC0CB | ⏳ Pending |
| Background Graphic | Wallpaper image | 1080x1920 (max 1440x2560) | ⏳ Pending |
| Login Button Color | Hex code | #FFC0CB | ⏳ Pending |

### Background Graphic Specifications
- **Format**: SVG/PNG
- **Optimal Size**: 1080x1920
- **Maximum Size**: 1440x2560
- **File Size**: Maximum 2 MB

---

## 7. Implementation Checklist

### Phase 1: Documentation & Planning
- [ ] Logo design and approval
- [ ] Subdomain allocation confirmation
- [ ] SSL certificate procurement
- [ ] Email setup confirmation

### Phase 2: DNS Configuration
- [ ] Configure CNAME records for all subdomains
- [ ] Verify DNS propagation
- [ ] Test subdomain accessibility

### Phase 3: SSL Implementation
- [ ] Install SSL certificates
- [ ] Configure SSL for all subdomains
- [ ] Test HTTPS functionality

### Phase 4: Branding Implementation
- [ ] Upload company logo
- [ ] Configure login page branding
- [ ] Set up email notifications
- [ ] Test system functionality

---

## 8. Cost Breakdown

| Item | Cost | Frequency | Notes |
|------|------|-----------|-------|
| SSL Certificate (if purchased separately) | $90 | One-time | Optional - Rafinita can provide |
| SSL Certificate (Rafinita provided) | $90 | Monthly | Included in monthly payment |
| System Setup | Included | One-time | Part of initial setup |

---

## 9. Contact Information

**Next Steps**: 
1. Confirm invoice payment for setup
2. Provide all required assets and information
3. Begin system creation and branding

**Timeline**: System creation will begin once all requirements are confirmed and assets are provided.

---

## 10. Notes

- All subdomains should be configured before SSL installation
- SSL certificates must be valid and not self-signed
- Logo must be provided in SVG format for optimal quality
- Background graphics should be optimized for web use
- All branding elements should maintain consistency with company identity

---

*Last Updated: [Current Date]*
*Status: Awaiting Confirmation* 

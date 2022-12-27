# Service Finder — Community Service Directory & Consumer Protection Portal

A community-driven web platform designed to connect residents of **Bahria Town, Islamabad** with verified local service providers, independent technicians, and neighborhood businesses. Developed as a university social work and technology initiative, the project addresses consumer exploitation by introducing price transparency, peer-reviewed accountability, and structured service booking at the community level.

---

## Background & Problem Statement

In local markets across Pakistan, consumers frequently face arbitrary pricing, unreliable workmanship, and a lack of recourse when dealing with everyday service providers—ranging from plumbers, electricians, and auto mechanics to tailors, dairy suppliers, and domestic workers. Although consumer protection regulations exist on paper, limited public awareness and weak enforcement leave households reliant on word-of-mouth recommendations.

**Service Finder** bridges this gap by using technology as a grassroots safeguard:
- **Community Consensus & Transparency**: Enables residents within a defined neighborhood (beta-tested in Bahria Town) to rate, review, and vet local retailers and technicians based on firsthand experience.
- **Competitive Quoting**: Allows residents to post task requirements and receive bids from multiple providers, reducing price gouging.
- **Consumer Rights Awareness**: Integrates directory services with clear guidance on consumer rights and fair-trade practices.

---

## How It Works

The platform operates on a 6-step workflow connecting residents with service professionals:

1. **Provider Registration** — Local service providers and businesses register their profiles, service areas, working hours, and baseline rates.
2. **Task / Requirement Posting** — Residents describe the job they need done or browse top-rated providers directly by category.
3. **Provider Quotations** — Relevant providers in the vicinity review the task and submit competitive bids.
4. **Provider Selection** — The resident compares community ratings, past reviews, cost estimates, and availability to hire the most reliable option.
5. **Service Execution** — The selected professional completes the work at the scheduled time.
6. **Review & Performance Rating** — The resident rates the provider's quality, punctuality, and pricing fairness, strengthening the community trust index.

---

## Service Categories

The directory organizes neighborhood businesses and independent workers across 16 primary and sub-categories (defined in [`categories.csv`](./categories.csv)):

| Parent Category | Service Categories | Scope |
| :--- | :--- | :--- |
| **Home Maintenance** | Plumbers, Electricians, Carpenters, Domestic Services | Sanitary repairs, electrical wiring, woodwork, and household help |
| **Health Care** | Hospitals, Medical Specialists, Dentists | Clinics, specialist consultations, and dental care |
| **Automotive & Transport** | Cars Workshop, Car Wash, Rent A Car | Mechanical diagnostics, detailing, and local vehicle rentals |
| **Food & Daily Essentials** | Food Places, Home-Based Food Providers, Milk & Organic Produce | Restaurants, home kitchens, tiffin services, and fresh groceries |
| **Beauty & Wellness** | Barber, Beauty Parlour, Gym, Yoga | Salons, personal grooming, and fitness centers |
| **Education** | Schools, Tuition Centers | Local schooling and after-school academic coaching |
| **Lifestyle & Logistics** | Tailors, Courier Delivery Services, Marriage Halls | Custom stitching, local parcel dispatch, and event venues |

---

## Key Platform Features

- **Location & Category Search**: Filter providers by neighborhood sector, distance radius, and service specialty.
- **4-Step Booking System**: Streamlined scheduling flow from task description and slot selection to confirmation.
- **OTP Verification**: Built-in one-time password checks to prevent spam or fake bookings.
- **Provider Schedule & Geofencing**: Tools for providers to configure business hours, service areas, team members, and unavailability dates.
- **Invoicing & Payment Support**: Automated invoice generation with support for online and cash-on-delivery settlement.

---

## Repository Structure

```text
├── index.html                      # Interactive visual portal showcasing categories, workflow, and providers
├── categories.csv                  # Structured taxonomy of parent and child service categories
├── widgets.txt                     # Workflow shortcodes and portal configuration snippets
├── logo-1.png / logo.psd           # Brand identity assets and source PSD
├── banner-main.png                 # Homepage hero banners and category tiles (*.png)
├── documentation-for-admin/        # Reference guide for platform administration & theme settings
└── documentation-for-features/     # Reference documentation for booking flows & provider tools
```

---

## Project Team

- **Omer Muneer**
- **Sohaib Ahmed**
- **Hassaan Naveed**
- **Muhammad Yasaal**

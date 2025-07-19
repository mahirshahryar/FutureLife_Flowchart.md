# Future Life User Journey Flowchart

```mermaid
graph TD
    subgraph Future Life Platform User Journeys
        A[Start: User Need] -->|School Supplies| B1[Discovery: Hears about platform<br>via ad/classmate]
        A -->|Jobs| B2[Discovery: Finds job board<br>via newsletter]
        A -->|Rentals| B3[Discovery: Finds rentals<br>via search engine]
        A -->|Deals| B4[Discovery: Sees deals<br>via social media]
        A -->|Community| B5[Discovery: Finds community<br>via orientation email]

        %% School Supplies Flow
        B1 --> C1[Exploration: Search for item<br>e.g., textbook, filter by price/condition]
        C1 --> D1[Decision: Select item<br>Check reviews, add to cart]
        D1 --> E1[Checkout: Choose pickup/delivery<br>Enter payment details]
        E1 --> F1[Delivery: Receive item<br>Campus pickup or courier]

        %% Jobs Flow
        B2 --> C2[Exploration: Filter jobs<br>e.g., part-time, near campus]
        C2 --> D2[Decision: Apply for job<br>Upload resume, submit form]
        D2 --> E2[Checkout: Submit application<br>Receive confirmation]
        E2 --> F2[Completion: Get interview<br>Start job if hired]

        %% Rentals Flow
        B3 --> C3[Exploration: Filter rentals<br>by price/location/lease term]
        C3 --> D3[Decision: Contact landlord<br>Schedule virtual tour]
        D3 --> E3[Checkout: Sign lease<br>Pay deposit]
        E3 --> F3[Delivery: Move in<br>Receive keys/access]

        %% Deals Flow
        B4 --> C4[Exploration: Browse deals<br>Filter by category/location]
        C4 --> D4[Decision: Select deal<br>e.g., restaurant discount]
        D4 --> E4[Checkout: Claim deal<br>Receive QR code]
        E4 --> F4[Completion: Use deal<br>Redeem at vendor]

        %% Community Flow
        B5 --> C5[Exploration: Search for groups/events<br>e.g., study group]
        C5 --> D5[Decision: Join group<br>RSVP for event]
        D5 --> E5[Checkout: Confirm attendance<br>Receive event details]
        E5 --> F5[Completion: Attend event<br>Connect with peers]
    end

    %% Styling for clarity
    classDef stage fill:#f9f9f9,stroke:#333,stroke-width:2px;
    class A,B1,B2,B3,B4,B5,C1,C2,C3,C4,C5,D1,D2,D3,D4,D5,E1,E2,E3,E4,E5,F1,F2,F3,F4,F5 stage;

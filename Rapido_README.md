# Rapido Captain Trust Check

Independent product case study exploring how Rapido riders could make a more informed decision after a captain accepts a booking. This is not an official Rapido feature; the prototype uses illustrative sample data.

## 1. Product Problem

After a captain accepts a ride, passengers may want clearer information before deciding whether to continue. The screenshots reviewed for this case study show that Rapido already displays some captain details and reliability cues, including an “Always on time” badge and a “Check” option for a potentially better captain nearby. The exact behaviour of the existing Check flow has not been verified, so this project explores how to make the decision and available information clearer rather than assuming the app has no existing controls.

## 2. Proposed Solution

Add a Captain Trust Check card to the existing assigned-captain screen. The card presents available captain information—rating and number of ratings, completed rides, tenure, relevant reliability badges, and identity/vehicle verification status where supported. Passengers choose **Continue with Captain** or **Find Another Captain**. Unavailable or unreliable statistics are hidden, and newer captains are labelled transparently. Ratings and trip history provide context; they do not guarantee safety.

## 3. Estimated Impact

The feature aims to help passengers feel better informed while monitoring the impact on cancellations and pickup time.

| Scenario | Estimated annual incremental revenue | Assumed retention improvement |
|---|---:|---:|
| Low | ₹10 crore | +3% |
| Base | ₹20 crore | +5% |
| High | ₹30 crore | +7% |

These are illustrative planning scenarios, not Rapido forecasts or measured results. The relationship between this feature, customer retention and revenue has not yet been validated. The proposed primary metric is the percentage of passengers who report having enough information to decide; also monitor continuation rate, captain-related cancellations, rematching and pickup delays.

## 4. User Journey & Where the Solution Is Added

1. **Home and destination:** The passenger enters pickup and destination details.
2. **Ride options:** The passenger selects Bike, reviews the fare and books.
3. **Matching:** Rapido searches for an available captain.
4. **Assigned captain — feature insertion point:** After a captain accepts, the existing assigned-captain screen gains the Captain Trust Check card. It shows the available profile and reliability information and asks the passenger to continue or find another captain.
5. **Continue:** The passenger proceeds with the assigned captain into the existing active-ride flow.
6. **Find another captain:** The passenger sees a notice that rematching may take longer, confirms the request, and returns to matching. A replacement captain is shown for review; if none is available, the prototype offers recovery options.

The prototype is a self-contained HTML demo. Captain details, statistics, matching and rematching outcomes are sample data and are not connected to Rapido systems.

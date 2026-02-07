Spectre Analytics

Spectre Analytics is a real-time energy monitoring and anomaly detection dashboard designed to identify hidden power waste and convert it into clear operational and financial insight. The project was built during a 24-hour hackathon (Echelon 2.0) with the aim of creating a working system that highlights inefficiencies in energy usage that are usually overlooked.

The core idea behind Spectre Analytics is that energy loss is rarely caused by dramatic failures. In most real-world environments, waste appears in subtle forms such as:
• equipment running outside scheduled hours
• machines idling without producing output
• motors drawing more power than their normal baseline
• systems consuming energy without triggering alarms

Individually, these issues seem minor, but over time they result in significant financial loss and unnecessary carbon impact. Spectre Analytics treats energy consumption as a live, evolving system rather than a static report.

Spectre Analytics continuously monitors energy usage using simulated hourly telemetry data. It compares expected consumption against actual usage in real time, detects abnormal behavior, and flags energy waste automatically. Detected issues are classified into two categories:
• critical anomalies such as overloads, surges, and thermal risks
• invisible inefficiencies such as phantom loads, idle equipment, and off-schedule operation

Each detected event is logged with a timestamp, affected asset, severity, and estimated energy waste. Excess consumption is translated into monetary loss, allowing technical data to be understood in business terms.

All data used in this project is mock data. The dataset is designed to realistically simulate hourly energy telemetry, operational load patterns, and anomaly behavior commonly observed in industrial and commercial systems. This allows realistic testing of anomaly detection, incident tracking, and cost analysis without requiring live infrastructure.

The dashboard is divided into multiple views, each serving a different purpose. The overview view presents system health, total energy waste, efficiency status, live load behavior, and capacity utilization. The savings view focuses on financial impact, including money lost, burn rate, projected annual savings, and high-impact assets. The incidents view provides a detailed log of detected anomalies, including classification, affected assets, waste magnitude, and recommended actions.

The design philosophy behind Spectre Analytics emphasizes clarity and action. Instead of overwhelming users with raw technical data, the system prioritizes visibility, classification, and decision-making. The interface is intentionally designed to feel like an operations console, enabling engineers and decision-makers to quickly understand what is happening, why it matters, and what needs attention.

This project was built during Echelon 2.0, a 24-hour hackathon, under strict time constraints that required rapid prioritization, clear thinking, and effective collaboration.

(function () {
  const interpretationBox = document.getElementById("clinical-interpretation");
  if (!interpretationBox) return;

  function updateInterpretation() {
    const mallampati = document.getElementById("mallampati")?.value || "";
    const tongue = document.getElementById("tongueObs")?.checked || false;

    if (!mallampati) {
      interpretationBox.innerHTML =
        "<em>Complete airway inputs to generate interpretation.</em>";
      return;
    }

    let risk = "LOW";
    if (mallampati === "II") risk = "MODERATE";
    if (mallampati === "III" || mallampati === "IV" || tongue) risk = "HIGH";

    const rationale = [];
    if (document.getElementById("soft")?.checked) rationale.push("Soft palate visible");
    if (document.getElementById("uvula")?.checked) rationale.push("Uvula visible");
    if (document.getElementById("pillars")?.checked) rationale.push("Faucial pillars visible");
    if (document.getElementById("hard")?.checked) rationale.push("Only hard palate visible");

    interpretationBox.innerHTML = `
      <strong>Airway Risk:</strong> ${risk}<br>
      <strong>Interpretation:</strong> Mallampati ${mallampati}
      ${tongue ? " with tongue obstruction noted." : "."}
      <br><br>
      <strong>Observed Findings:</strong><br>
      ${rationale.length ? rationale.join("<br>") : "—"}
    `;
  }

  ["mallampati", "tongueObs", "soft", "uvula", "pillars", "hard"].forEach(id => {
    const el = document.getElementById(id);
    if (el) el.addEventListener("change", updateInterpretation);
  });
})();

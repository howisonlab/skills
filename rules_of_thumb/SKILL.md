Process for deriving memorable numerical rules of thumb:

- Identify the exact formula. Even if complex, find the authoritative source. Know its valid range.
- Find a natural anchor. Look for a point where inputs and outputs are round, equal, or otherwise memorable. Symmetry helps (75/75/66).
- Linearize around the anchor. Most smooth functions are nearly linear locally. Compute exact partial derivatives for each input variable.
- Find rational approximations to the derivatives. Express as "per 5 units" or "per 10 units" to match how humans naturally chunk numbers. Prefer small integers. Favor operations that are cognitively free: ×2, ×10, ÷2, appending a zero. Chains of free operations compound well: ×2 then −10% costs almost no working memory and together yield factor 1.8 — often closer than any single-step approximation with an awkward constant. A two-step decomposition is often easier than one step with an awkward number (×1.8 or +9).
- Check if derivatives are symmetric or asymmetric. If asymmetric (like 3 left / 4 right), decide if the asymmetry is worth carrying or if a single round number is close enough.
- Quantify errors. Constant errors (like our column errors) are fine — they can be absorbed into a bump. Errors that grow with distance from anchor are more dangerous.
- Test at memorable boundary cases. Round numbers, extremes, common real-world values. If errors are tolerable, done.
- Compress to a sentence. Anchor + moves + any bump. If the sentence needs more than ~10 words of numbers, the rule is too complex. Prefer sentences where each operation can be done on the running total left-to-right, without holding intermediate values.
- Verify the sentence reconstructs the table. A rule that can't be executed under mild cognitive load isn't useful.

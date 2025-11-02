# Benchmarks & Evaluation

Systematic evaluation of different approaches.

## Subdirectories

### datasets/
Test sets derived from Papers with Code:
- Metadata listings with citation counts and publication dates
- Sample papers for each category
- Stratified subsets for fair comparison
- Ground truth annotations
- Papers sampled using PageRank-like weighting (citation counts) + recency bias
- Ensures evaluation focuses on impactful papers while including recent work

### metrics/
Evaluation frameworks:
- Structure preservation scorers
- Semantic completeness metrics
- LLM comprehension tests
- Token efficiency calculations
- Speed and memory benchmarks

### results/
Benchmark results and measurements:
- Performance tables
- Comparison matrices
- Statistical analysis
- Time/memory profiling results

### comparisons/
Side-by-side approach comparisons:
- Same paper processed different ways
- Quality vs. efficiency tradeoffs
- Approach strengths and weaknesses
- Recommendations by paper type

## Testing Methodology
1. Define evaluation criteria
2. Select representative papers from Papers with Code
3. Run each approach on test set
4. Measure and compare results
5. Analyze strengths/weaknesses
6. Document findings and recommendations

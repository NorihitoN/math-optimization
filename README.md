# math-optimization

## Directory Structure

math-optimization-repo/  # リポジトリのルート
│── README.md            # プロジェクトの概要、使用方法
│── LICENSE              # ライセンス設定（MIT, GPL など）
│── requirements.txt     # 必要なライブラリ（Python用）
│── docs/                # ドキュメント関連
│   ├── introduction.md  # 数理最適化の基本概念
│   ├── algorithms.md    # 主要な最適化アルゴリズムの解説
│   ├── references.md    # 関連文献や参考書籍リスト
│── optimization/        # 数理最適化の各種コード
│   ├── linear/          # 線形計画法（LP）
│   │   ├── simplex.py   # シンプレックス法の実装
│   │   ├── interior_point.py # 内点法
│   ├── nonlinear/       # 非線形最適化（NLP）
│   │   ├── gradient_descent.py # 勾配降下法
│   │   ├── newton_method.py    # ニュートン法
│   ├── combinatorial/   # 組合せ最適化
│   │   ├── tsp.py       # 巡回セールスマン問題
│   │   ├── knapsack.py  # ナップザック問題
│   ├── metaheuristics/  # メタヒューリスティクス
│   │   ├── genetic_algorithm.py  # 遺伝的アルゴリズム
│   │   ├── simulated_annealing.py # 焼きなまし法
│   │   ├── pso.py       # 粒子群最適化（PSO）
│   │   ├── de.py        # 差分進化（DE）
│── experiments/         # 実験コードやシミュレーション
│   ├── microgrid_optimization.py # マイクログリッドの最適化
│   ├── phev_charging.py         # PHEVの充電最適化
│── tests/              # テストコード
│   ├── test_linear.py  # 線形計画法のテスト
│   ├── test_nonlinear.py # 非線形最適化のテスト
│── notebooks/          # Jupyter Notebook
│   ├── linear_optimization.ipynb # 線形計画法の解説
│   ├── metaheuristics.ipynb # メタヒューリスティクスの解説


## Jupyter Notebook の命名規則
各Notebookは、以下のプレフィックス（カテゴリー）を使用して管理されます。

プレフィックス（カテゴリー）	説明
LP_	線形計画法（Linear Programming）
NLP_	非線形計画法（Nonlinear Programming）
IP_	整数計画法（Integer Programming）
CP_	制約プログラミング（Constraint Programming）
GA_	遺伝的アルゴリズム（Genetic Algorithm）
PSO_	粒子群最適化（Particle Swarm Optimization）
DE_	差分進化（Differential Evolution）
SA_	焼きなまし法（Simulated Annealing）
TSP_	巡回セールスマン問題（Traveling Salesman Problem）
Knapsack_	ナップザック問題（Knapsack Problem）
Microgrid_	マイクログリッド最適化
PHEV_	PHEVの充電最適化
Meta_	メタヒューリスティクス全般

### Jupyter Notebook の一覧

`notebooks/` ディレクトリ内には、以下のJupyter Notebookが含まれています。

- **LP_Simplex_Method_v1.ipynb**: シンプレックス法
- **NLP_Gradient_Descent_v2.ipynb**: 勾配降下法
- **DE_Differential_Evolution_v1.ipynb**: 差分進化
- **GA_Genetic_Algorithm_v1.ipynb**: 遺伝的アルゴリズム
- **PSO_Particle_Swarm_v1.ipynb**: 粒子群最適化
- **TSP_Solver_v1.ipynb**: 巡回セールスマン問題
- **Microgrid_Optimization_v1.ipynb**: マイクログリッド最適化
- **PHEV_Charging_Schedule_v1.ipynb**: PHEVの充電スケジュール最適化
- **Metaheuristics_Comparison_v1.ipynb**: メタヒューリスティクス比較
# 🚀 Kubeflow Contributions

## 🧠 Open Source Work
Contributions to Kubeflow Pipelines (React, TypeScript, React Query)

---

## 🔹 Fix: Prevent Spinner on Background Refetch

- 🔗 PR: https://github.com/kubeflow/pipelines/pull/13199
- ✅ Status: Merged into main branch
- 🛠️ Area: Frontend (React Query state management)

---

## 💡 Problem
The UI spinner was incorrectly triggered during background data refetches due to the use of `isFetching`.

This caused unnecessary loading indicators even when cached data was available.

---

## ⚙️ Solution
Replaced `isFetching` with `isLoading`:

- `isLoading` → triggers only on initial load  
- `isFetching` → triggers on every refetch  

This ensures the spinner appears only when needed.

---

## 🔧 Tech Stack
- ⚛️ React
- 🟦 TypeScript
- 🔁 React Query

---

## 🎯 Impact
- Improved UX by eliminating unnecessary spinner flicker  
- Aligns UI behavior with React Query best practices  
- Fix merged into Kubeflow production codebase  

---

## 🧩 Key Learnings
- Deep understanding of React Query states  
- Handling cached vs refetch data correctly  
- Real-world open source PR workflow  

---

## 🌟 Achievement
✔️ Successfully contributed to a large-scale open source project (Kubeflow)  
✔️ Code reviewed, refined, and merged by maintainers  

---

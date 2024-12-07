# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug where the `useEffect` hook runs on every render due to a missing dependency in the dependency array.  The bug results in an infinite loop of console logs, and potentially performance issues. The solution shows how to fix this by including `count` in the dependency array.
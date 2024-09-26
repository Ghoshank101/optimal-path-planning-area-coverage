# Optimal Path Planning for Multiple UAV Area Coverage

## Ongoing Project

## Introduction and Goals

Unmanned Aerial Vehicles (UAVs) have become essential for collecting data from hard-to-reach places. Thanks to advancements in electronics and airframe technology, smaller and more affordable UAVs are now available for a range of tasks, including surveillance, search and rescue, wildlife monitoring, and border patrol.

One of the critical tasks for UAVs is **effective area coverage**. The challenge is to design flight paths that ensure complete coverage of the area as efficiently as possible. 

Using multiple UAVs to cover a given area presents an efficient solution. However, optimizing the paths of these UAVs or determining the number of UAVs required for a specific area remains an open industry challenge.

Research in this domain highlights **area decomposition into cells and path planning inside these cells**, as seen in [1], [2]. This approach, known as **area sweeping**, will be explained in detail in Section III.

### Goals

1. **Formulate an algorithm** to convert any general area input into a convex *n*-sided polygon with minimal redundant area coverage.
2. Determine the **optimal sweep direction** based on the polygon's diameter and calculate the optimal number *n* of UAVs required to cover the area.
3. Develop an **area-slicing algorithm** to divide the polygon into lanes, ensuring no UAV enters another's area, thus avoiding collisions.
4. Implement a **suitable search pattern** (zigzag, spiral, Dubin’s path, etc.) for UAV path planning within the cells, optimizing for minimum time while accounting for overlap between lanes due to uncertainties like winds or camera errors.

---

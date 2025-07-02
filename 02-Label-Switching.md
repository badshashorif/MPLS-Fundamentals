# Label Switching ব্যাখ্যা

MPLS Router packet receive করার সাথে সাথেই IP header না দেখে Label দেখে Forward করে দেয়। এজন্য Label Forwarding Table (LFIB) maintain করে।

- Ingress Router: Label assign করে
- Intermediate Router: Label swap করে
- Egress Router: Label remove করে

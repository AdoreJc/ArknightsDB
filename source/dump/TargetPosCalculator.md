# TargetPosCalculator

**Namespace:** ` `


## Fields

- `Boolean m_isTransLocalConformed`

- `Camera m_selfCamera`

- `RectTransform m_transLocal`

- `Camera m_targetCamera`

- `GameObject m_target`

- `RectTransform m_transTarget`


## Methods

- `Boolean PrepareSelf(GameObject, RectTransform)`

- `Boolean _PrepareForNewTarget(GameObject)`

- `Boolean _PrepareForTransLocal(RectTransform)`

- `Bounds CalcTargetItemBounds()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TargetPosCalculator : IHotfixable
{
	private Boolean m_isTransLocalConformed; // 0x10
	private Camera m_selfCamera; // 0x18
	private RectTransform m_transLocal; // 0x20
	private Camera m_targetCamera; // 0x28
	private GameObject m_target; // 0x30
	private RectTransform m_transTarget; // 0x38
	private static DelegateBridge __Hotfix0_PrepareSelf; // 0x0
	private static DelegateBridge __Hotfix0__PrepareForNewTarget; // 0x8
	private static DelegateBridge __Hotfix0__PrepareForTransLocal; // 0x10
	private static DelegateBridge __Hotfix0_CalcTargetItemBounds; // 0x18
	private static DelegateBridge __Hotfix0__CalcTargetInSameCamera; // 0x20
	private static DelegateBridge __Hotfix0__CalcTargetWithDiffCamera; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x218d65c VA: 0x75947a565c
	public Boolean PrepareSelf(GameObject curTarget, RectTransform transLocal) { }
	// RVA: 0x218f520 VA: 0x75947a7520
	private Boolean _PrepareForNewTarget(GameObject target) { }
	// RVA: 0x218f788 VA: 0x75947a7788
	private Boolean _PrepareForTransLocal(RectTransform transLocal) { }
	// RVA: 0x218d74c VA: 0x75947a574c
	public Bounds CalcTargetItemBounds() { }
	// RVA: 0x218f8e8 VA: 0x75947a78e8
	private static Bounds _CalcTargetInSameCamera(RectTransform target, RectTransform local) { }
	// RVA: 0x218fa74 VA: 0x75947a7a74
	private static Bounds _CalcTargetWithDiffCamera(RectTransform target, Camera targetCamera, RectTransform local, Camera localCamera) { }
	// RVA: 0x218f3e4 VA: 0x75947a73e4
	public Void .ctor() { }
}
```
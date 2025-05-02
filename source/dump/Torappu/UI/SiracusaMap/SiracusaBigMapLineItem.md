# SiracusaBigMapLineItem

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `AnimationClip _clipExpand`

- `RectTransform _transLine`

- `Single _lineExpandDur`


## Methods

- `Void Reset(Options)`

- `Void _DoExpandAnim(Single, Single)`

- `Void _CleanAllTweens()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaBigMapLineItem : MonoBehaviour, IHotfixable
{
	private AnimationClip _clipExpand; // 0x18
	private RectTransform _transLine; // 0x20
	private Single _lineExpandDur; // 0x28
	private List`1 m_tweens; // 0x30
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0__DoExpandAnim; // 0x8
	private static DelegateBridge __Hotfix0__CleanAllTweens; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2408f48 VA: 0x7594a20f48
	public Void Reset(Options options) { }
	// RVA: 0x24092dc VA: 0x7594a212dc
	private Void _DoExpandAnim(Single lineLength, Single preDelay) { }
	// RVA: 0x2409114 VA: 0x7594a21114
	private Void _CleanAllTweens() { }
	// RVA: 0x24096cc VA: 0x7594a216cc
	public Void .ctor() { }
}
```
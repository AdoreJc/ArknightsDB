# EnemyDuelRoundEndStandPlayerInfoView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `GameObject _objMine`

- `Text _textNameMine`

- `Image _imgAvatarMine`

- `GameObject _objOtherNormal`

- `Text _textNameOtherNormal`

- `Image _imgAvatarOtherNormal`

- `GameObject _objOtherShieldBroken`

- `Text _textNameOtherShieldBroken`

- `Image _imgAvatarOtherShieldBroken`

- `GameObject _objWin`

- `GameObject _objChampion`

- `GameObject _objShieldBroken`

- `GameObject _objShield`

- `GameObject _objOut`

- `Text _textNameOut`

- `UIAnimationLocation _animChampion`

- `UIAnimationLocation _animOut`

- `UIAnimationLocation _animShieldBreak`

- `UIPageFinder m_pageFinder`

- `Tween m_tweenWin`

- `Tween m_tweenChampion`

- `Tween m_tweenOut`

- `Tween m_tweenShieldBreak`


## Methods

- `Void ApplyData(String, EnemyDuelPlayerData, Int32, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelRoundEndStandPlayerInfoView : MonoBehaviour, IHotfixable
{
	private GameObject _objMine; // 0x18
	private Text _textNameMine; // 0x20
	private Image _imgAvatarMine; // 0x28
	private GameObject _objOtherNormal; // 0x30
	private Text _textNameOtherNormal; // 0x38
	private Image _imgAvatarOtherNormal; // 0x40
	private GameObject _objOtherShieldBroken; // 0x48
	private Text _textNameOtherShieldBroken; // 0x50
	private Image _imgAvatarOtherShieldBroken; // 0x58
	private GameObject _objWin; // 0x60
	private GameObject _objChampion; // 0x68
	private GameObject _objShieldBroken; // 0x70
	private GameObject _objShield; // 0x78
	private GameObject _objOut; // 0x80
	private Text _textNameOut; // 0x88
	private UIAnimationLocation _animChampion; // 0x90
	private UIAnimationLocation _animOut; // 0xa0
	private UIAnimationLocation _animShieldBreak; // 0xb0
	private UIPageFinder m_pageFinder; // 0xc0
	private Tween m_tweenWin; // 0xd0
	private Tween m_tweenChampion; // 0xd8
	private Tween m_tweenOut; // 0xe0
	private Tween m_tweenShieldBreak; // 0xe8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__PlayAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x298f6f4 VA: 0x7594fa76f4
	public Void ApplyData(String actId, EnemyDuelPlayerData data, Int32 curRoundIndex, Boolean isProtectedRound, Boolean isLastRound) { }
	// RVA: 0x298fc90 VA: 0x7594fa7c90
	private static Void _PlayAnim(UIAnimationLocation anim, ref Tween tween) { }
	// RVA: 0x298fd90 VA: 0x7594fa7d90
	public Void .ctor() { }
}
```
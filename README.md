# Physx Sample
Physxを試してみるレポジトリ

## 参考にしたURL
- [GitHub - NVIDIA PhysX](https://github.com/NVIDIA-Omniverse/PhysX)
- [Zenn - 物理エンジンPhysXを触ってみよう](https://zenn.dev/hama1080/books/c107c7c945018a)
- [GitHub - PhysicsEnginePrimer](https://github.com/hama1080/PhysicsEnginePrimer)

## メモ
- [4系](https://github.com/NVIDIAGameWorks/PhysX)はWindows、Linux、Android、Mac、iOSに対応している。<br>しかし、[vcpkgでfind_packageに対応していない](https://github.com/microsoft/vcpkg/issues/10233)みたい。
- [5系](https://github.com/NVIDIA-Omniverse/PhysX)はWindows、Linuxに対応している。 ※当レポジトリでは5系を使用している。<br>
[vcpkgでfind_package](https://vcpkg.roundtrip.dev/ports/physx)にも対応している。<br>
[非公式でMac、iOS、Androidに対応したfork](https://github.com/o3de/PhysX)が存在するが、vcpkgでパッケージが提供されているのは公式版だけみたい。

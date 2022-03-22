# Resume React Hook

## Introduction React Hook
Hooks merupakan fitur baru di React 16.8. Dengan Hooks, kita dapat menggunakan state dan fitur React yang lain tanpa perlu menulis sebuah kelas.<br>

Hooks pada react terbagi menjadi 2 yaitu :
1. Hooks dasar :
   * useState
   * useEffect
   * useContext
<br>

2. Hooks Tambahan :
   * useReducer
   * useCallback
   * useMemo
   * useRef
   * useImperativeHandle
   * useLayoutEffect
   * useDebugValue
<br>

Aturan Pada Hooks :
1. Hanya Panggil Hooks di tingkat atas
   Jangan memanggil hooks dari dalam loops, condition, atau nested function.
2. Hanya Panggil Hooks dari fungsi fungsi react
   Jangan memanggil hooks dari fungsi fungsi javascript biasa. Kita dapat : 
   * Memanggil hooks dari komponen komponen fungsi react.
   * memanggil hooks dari custom hooks

## UseState dan UseEffect
UseState hanya bisa digunakan menggunakan function bukan digunakan di class component.<br>
useEffect
* effect hook memungkinkan kita melakukan efek samping (side effects) di dalam function component
* effect hook akan berjalan ketika componentDidMount, componentDidUpdate, dan componentWillUnmount = useEffect
* ada dua jenis : Butuh pembersihan dan tidak butuh pembersihan

## Membuat Custom Hook
Membuat Hook Kita sendiri memungkinkan Kita mengekstrak komponen logika ke fungsi yang dapat digunakan lagi.


# Uraian Praktikum
Mengubah class component pada tugas praktikum sebelumnya menjadi function component, serta menggunakan react hooks.

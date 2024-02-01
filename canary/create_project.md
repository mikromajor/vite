npm init vite react-canary
cd react-canary
npm i
npm i react@18.3.0-canary-247738465-20240130 react-dom@18.3.0-canary-247738465-20240130

Якщо використовуєте TypeScript, потрібно оновити секцію compilerOptions в tsConfig.json та додати типи: "types": [ "react/canary", "react-dom/canary" ]

Канарковий реліз відкриває доступ до:

1. import { use } from 'react'
2. import { useOptimistic } from 'react'
3. import { useFormStatus } from 'react-dom'
4. import { useFormState } from 'react-dom'
5. 'use client'
6. 'use server'
7. form🤯
8. cache

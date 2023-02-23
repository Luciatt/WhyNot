<template>

</template>

<script setup>
import { shallowMount } from '@vue/test-utils'
import TestComponent from '@/tests/unit/TestComponent.vue'

describe('TestComponent', () => {
  it('renders', () => {
    const wrapper = shallowMount(TestComponent)
    expect(wrapper.exists()).toBe(true)
  })
  it('has a card', () => {
    const wrapper = shallowMount(TestComponent)
    expect(wrapper.vm.$options.Card).toMatch('TestComponent')
  })
})

</script>
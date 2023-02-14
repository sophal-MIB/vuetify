<template>
  <v-container fluid>
    <v-textarea
      clearable
      clear-icon="mdi-close-circle"
      v-model="message"
      label="Text"
      model-value="This is clearable text."
    ></v-textarea>
  </v-container>
</template>

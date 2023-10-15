---
title: Contact
layout: contact
description: Contact
---


<script src="https://unpkg.com/tailwindcss-jit-cdn"></script>
<div class="w-full md:max-w-full mx-auto">
  <div class="p-6 border border-gray-300 sm:rounded-md">
    <form
      method="POST"
      action="https://public.herotofu.com/v1/eb093e90-6b63-11ee-80c8-136eb968d513"
      enctype="multipart/form-data"
    >
      <label class="block mb-6">
        <span class="text-gray-700">Your name</span>
        <input
          name="name"
          type="text"
          class="
            block
            w-full
            mt-1
            border-gray-300
            rounded-md
            shadow-sm
            focus:border-indigo-300
            focus:ring
            focus:ring-indigo-200
            focus:ring-opacity-50
          "
          placeholder="Joe Bloggs"
        />
      </label>
      <label class="block mb-6">
        <span class="text-gray-700">Email address</span>
        <input
          name="email"
          type="email"
          class="
            block
            w-full
            mt-1
            border-gray-300
            rounded-md
            shadow-sm
            focus:border-indigo-300
            focus:ring
            focus:ring-indigo-200
            focus:ring-opacity-50
          "
          placeholder="joe.bloggs@example.com"
        />
      </label>
      <label class="block mb-6">
        <span class="text-gray-700">Requirement documents</span>
        <input
          name="receipt"
          type="file"
          class="
            block
            w-full
            mt-1
            focus:border-indigo-300
            focus:ring
            focus:ring-indigo-200
            focus:ring-opacity-50
          "
        />
      </label>
      <label class="block mb-6">
        <span class="text-gray-700">Please describe your requirement</span>
        <textarea
          name="message"
          class="
            block
            w-full
            mt-1
            border-gray-300
            rounded-md
            shadow-sm
            focus:border-indigo-300
            focus:ring
            focus:ring-indigo-200
            focus:ring-opacity-50
          "
          rows="3"
          placeholder="Please describe your requirement"
        ></textarea>
      </label>
      <div class="mb-6">
        <button
          type="submit"
          class="
            h-10
            px-5
            text-indigo-100
            bg-indigo-700
            rounded-lg
            transition-colors
            duration-150
            focus:shadow-outline
            hover:bg-indigo-800
          "
        >
          Submit
        </button>
      </div>
    </form>
  </div>
</div>



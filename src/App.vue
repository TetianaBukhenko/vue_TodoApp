<template>
  <section class="todoApp">
    <h1 class="todoApp__title">Todos</h1>
    <section class="todoApp__content box">
     <header class="box"> 
      <button
        type="button"
        className="todoApp__button active"
      ></button>
      <form>
        <input
          class="todoApp__input"
          type="text"
          placeholder="What needs to be done?"
        />
      </form>
     </header>

     <section class="box todoApp__main">
      <div class="todo completed"><label class="todo__status-label">
        <input type="checkbox" class="todo__status"/>
      </label> 
        <span>todo</span></div>
      <div class="todo">todo1</div>
      <div class="todo">todo1</div>
     </section>
     <footer class="todoApp__footer">
      <div>
        0 items left
      </div>

      <div class="todoApp__buttons">
        <button class="button is-info is-light">All</button>
        <button class="button is-warning is-light">Active</button>
        <button class="button is-success is-light">Completed</button>
      </div>

      <button class="button is-danger is-light">Clear completed</button>
     </footer>
    </section>
    <div class="notification is-danger is-light box">Something went wrong!</div>
  </section>
</template>

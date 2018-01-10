<template>
<div class="home">
  <section class="hero">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">{{ heading }}</h1>
        <div class="is-two-thirds column is-paddingless">
          <h2 class="subtitle is-4">{{ subheading }}</h2>
        </div>
        <a class="button is-large is-primary" id="learn">Learn more</a>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container">
      <div class="columns pd is-desktop">
        <div class="column is-1 has-text-centered">
          <i class="fa fa-cog is-primary"></i>
        </div>
        <div class="column">
          <p class="title"><strong>We provide superior logistics so that your business can succeed in a crazy world.</strong></p>
        </div>
        <div class="column">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.</strong>
          </p>
        </div>
      </div>
    </div>

    <div class="columns pd">
      <div class="column">
        <div class="card">
          <div class="card-content">
            <p class="title">"I think it's an absolutely excellent tool for our business. I can't survive without this thing."</p>
            <p class="subtitle">- Gary Simon</p>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-content">
            <p class="title">"I think it's an absolutely excellent tool for our business. I can't survive without this thing."</p>
            <p class="subtitle">- Gary Simon</p>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-content">
            <p class="title">"I think it's an absolutely excellent tool for our business. I can't survive without this thing."</p>
            <p class="subtitle">- Gary Simon</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</div>
</template>

<script>
export default {
  name: 'home',
  data() {
    return {
      heading: 'Soaring to new heights.',
      subheading: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'

.hero
  background: url('data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw0NDQ0NDQ8NDQ0NDQ0NDQ0NDQ8NDQ0NFREWFhURFRUYHSggGBolGxUVITEhJSkrLjouFx8zODM4Nyg5LjcBCgoKDQ0NDg0NDysZFRk3LSstLSsrKzctKy0rKysrKysrKy0rLS0rKysrKysrKysrKysrKysrKysrKysrKysrK//AABEIALcBEwMBIgACEQEDEQH/xAAZAAEBAQEBAQAAAAAAAAAAAAADAAECBAX/xAAXEAEBAQEAAAAAAAAAAAAAAAAAEhEB/8QAGQEBAQEBAQEAAAAAAAAAAAAAAAEDAgYF/8QAFREBAQAAAAAAAAAAAAAAAAAAABH/2gAMAwEAAhEDEQA/APm4sd4sejfGcYsd4sBxix3iwB4sJjMBxix3iwB4sd4sBwsd4sAeLHeLAcYsd4sAeLCYzAcYsd4sAeKXeLAcYpd4sAeLCYsAeLCYsUHiwmMwHGLHeLAHiJiB6sWExS5oPGd4XFJQWLCSpKDxYTFJQeMwsskoPFjuW4UFiwmLAHiwmMkHGMwmKQHiwkslQeLCSpAeLHeKQcYzCYsAeLHeLAcYsd4sBxjMJiwB4sJjMBxiJiB68WExY4oPGYXFgCxYTFhQeKSSsKDlmFxmFBypJKkoLFJZZi0HKkkrAHKwmLCgpWExYUFKkuMwoLFhcWFBYsJikoPGSXFhQUqS4zCg5UkxSApbJMWLQWIuIHrxYSVLhR4sJKkB4zCypQFiksswB4ySypAUqSSpUHjMLKkBYsJKwB4sJKkBYsJKwoLFhZZJQeKSYpAeMwsqSgsWExmA4xS7xYo4xmExYA8UkxYA5YXED2SpLLJcKOVJZZIClSWVIClSWVIClkllSApUllkgKVJZUgKVJZUgKVJZZIClSWWSApUllSoGVJZUlBSsLLJKClSWVIClSWWSA5ZhZWCClYSVgo5YWUEe6VJZUs6oZUmlSUDKk0qSoGVJZUrVFLJNKkoGVJpZJQMqTSpKBlSWVJQUqSypKBlkmlSUDLJNKkoGVJZUrQUsk0skqClSWVJVDKk0skqCxkmlklBSpLKkoHEWWlHulSaVLOuwypNKkoGVJZUlQMqTSpKBlSaWSUFLJNKkpAyyTSpUDKk0qQgZUllSAcUllSAZUmlklIKWSaWSUgpUllSUgZUllSUFLJNLJWgpUllklSClSWVJQMouIo+hKksqWVdilSWVK0gpZJZUpUFKksqVoKVJZUlAypNLJKBlSaWSUFKksqSgZUmlklAypNLJWgpZJpUlAypLKkoKWSaWSUDKk0skoKVJZUlAypLLJWgpUllSUDLSyij3ypLKljXcFKksqSgpUllSUgpUklSUg5ZJZUlIKWSbGYtBSyTYzCkFKksqSkFLJNKkpAyyTSpKkDLJNKkpAypNKlaQMsk0skpAypNLJKQUqSypKkDKksqSkDiwsqSkFjDSike7FhcWMq0g8ZhJUlIPFhJUlIPFhJUlIPGYWVJSCxSSVJSClSSVK0g5UklSUg5ZJZZJSDlkllYUgpUlxklIKVJcWFIKWSXFhUgsWExYtILFhZZJSClSWWSUg5ZJZUlIKUSWlI9uLHeLGNaRxKl3jcKQcqXeNwpByySYsWkHKkmLCkHLJLjMKkHKkmLCkHLJLjMKQcqSYsWkFKkuMwpB4zC4sKQWLCYsKQWLCSpKQWLCSpWpB4ySSpKQcsksskpB4sJjMKRxid40pHrxYkyaJYkCWJAsWJAsWJAsZiQLFiQLFjEosWJAsWMQLFiQixmNQMxmNQMxmNQMxYkozFiQMxYkosYkD//Z')
  background-size: cover
  .title
    color: #fff
    +mobile
      font-weight: bold
    +tablet
      font-size: 2.5rem
    +desktop
      font-size: 4rem
      margin-top: 2rem

h2
  margin: 1.5rem 0 2rem 0 !important
  color: #fff

.fa-cog
  font-size: 40px
  color: $primary

#learn
  +desktop
    margin-bottom: 2rem

.pd
  +tablet
    padding: 2em 0

</style>

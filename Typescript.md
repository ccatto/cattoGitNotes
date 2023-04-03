# Typescript Errors

### The idea of this page is to document my typescript errors that I work though;

Property 'home' is missing in type '{ children: any[]; }' but required in type '{ children: any; home: any; }'.ts(2741)

````
export default function Post({ postData }) {
    return (
      <Layout>
        {postData.title}
        <br />
        {postData.id}
        <br />
        {postData.date}
      </Layout>
    );
````

